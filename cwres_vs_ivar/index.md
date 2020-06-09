## CWRES vs IVAR

```@raw html
<pre class='hljl'>
<span class='hljl-k'>using</span><span class='hljl-t'> </span><span class='hljl-n'>Pumas</span><span class='hljl-p'>,</span><span class='hljl-t'> </span><span class='hljl-n'>PumasPlots</span><span class='hljl-p'>,</span><span class='hljl-t'> </span><span class='hljl-n'>StatsPlots</span><span class='hljl-t'>
</span><span class='hljl-nf'>include</span><span class='hljl-p'>(</span><span class='hljl-s'>&quot;model.jl&quot;</span><span class='hljl-p'>)</span><span class='hljl-t'>

</span><span class='hljl-k'>using</span><span class='hljl-t'> </span><span class='hljl-n'>Pumas</span><span class='hljl-t'> </span><span class='hljl-n'>PumasPlots</span><span class='hljl-t'>

</span><span class='hljl-n'>p</span><span class='hljl-t'> </span><span class='hljl-oB'>=</span><span class='hljl-t'> </span><span class='hljl-nd'>@df</span><span class='hljl-t'> </span><span class='hljl-n'>res</span><span class='hljl-t'> </span><span class='hljl-nf'>scatter</span><span class='hljl-p'>(</span><span class='hljl-sc'>:time</span><span class='hljl-p'>,</span><span class='hljl-t'> </span><span class='hljl-sc'>:dv_wres</span><span class='hljl-p'>;</span><span class='hljl-t'> </span><span class='hljl-n'>xlabel</span><span class='hljl-t'> </span><span class='hljl-oB'>=</span><span class='hljl-t'> </span><span class='hljl-s'>&quot;Time&quot;</span><span class='hljl-p'>,</span><span class='hljl-t'> </span><span class='hljl-n'>ylabel</span><span class='hljl-t'> </span><span class='hljl-oB'>=</span><span class='hljl-t'> </span><span class='hljl-s'>&quot;Weighted residuals&quot;</span><span class='hljl-p'>)</span><span class='hljl-t'>
</span><span class='hljl-cs'># Zero-line</span><span class='hljl-t'>
</span><span class='hljl-nf'>hline!</span><span class='hljl-p'>(</span><span class='hljl-n'>p</span><span class='hljl-p'>,</span><span class='hljl-t'> </span><span class='hljl-p'>[</span><span class='hljl-ni'>0</span><span class='hljl-p'>];</span><span class='hljl-t'> </span><span class='hljl-n'>linestyle</span><span class='hljl-t'> </span><span class='hljl-oB'>=</span><span class='hljl-t'> </span><span class='hljl-sc'>:dash</span><span class='hljl-p'>)</span><span class='hljl-t'>


</span>
</pre>

```
```@raw html

<div style="display:inline-block">
    <p style="display:inline-block; text-align: center">
        <img src="https://gallery.pumas.ai/cwres_vs_ivar/media/image.png" alt="">

    </p>
</div>

<div style="display:inline-block">
    <p style="display:inline-block; text-align: center">
        <img src="https://gallery.pumas.ai/cwres_vs_ivar/media/image.svg" alt="">

    </p>
</div>

```
