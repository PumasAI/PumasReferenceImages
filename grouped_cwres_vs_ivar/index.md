## Grouped CWRES vs IVAR

```@raw html
<pre class='hljl'>
<span class='hljl-k'>using</span><span class='hljl-t'> </span><span class='hljl-n'>Pumas</span><span class='hljl-p'>,</span><span class='hljl-t'> </span><span class='hljl-n'>PumasPlots</span><span class='hljl-p'>,</span><span class='hljl-t'> </span><span class='hljl-n'>StatsPlots</span><span class='hljl-t'>
</span><span class='hljl-nf'>include</span><span class='hljl-p'>(</span><span class='hljl-s'>&quot;model.jl&quot;</span><span class='hljl-p'>)</span><span class='hljl-t'>

</span><span class='hljl-k'>using</span><span class='hljl-t'> </span><span class='hljl-n'>Pumas</span><span class='hljl-t'> </span><span class='hljl-n'>PumasPlots</span><span class='hljl-t'>

</span><span class='hljl-nf'>plot_grouped</span><span class='hljl-p'>(</span><span class='hljl-nf'>groupby</span><span class='hljl-p'>(</span><span class='hljl-nf'>DataFrame</span><span class='hljl-p'>(</span><span class='hljl-nf'>inspect</span><span class='hljl-p'>(</span><span class='hljl-n'>res</span><span class='hljl-p'>)),</span><span class='hljl-t'> </span><span class='hljl-sc'>:id</span><span class='hljl-p'>)[</span><span class='hljl-ni'>1</span><span class='hljl-oB'>:</span><span class='hljl-ni'>9</span><span class='hljl-p'>];</span><span class='hljl-t'> </span><span class='hljl-n'>legend</span><span class='hljl-t'> </span><span class='hljl-oB'>=</span><span class='hljl-t'> </span><span class='hljl-sc'>:none</span><span class='hljl-p'>)</span><span class='hljl-t'> </span><span class='hljl-k'>do</span><span class='hljl-t'> </span><span class='hljl-n'>subdf</span><span class='hljl-t'>
    </span><span class='hljl-nd'>@df</span><span class='hljl-t'> </span><span class='hljl-n'>subdf</span><span class='hljl-t'> </span><span class='hljl-nf'>scatter</span><span class='hljl-p'>(</span><span class='hljl-sc'>:time</span><span class='hljl-p'>,</span><span class='hljl-t'> </span><span class='hljl-sc'>:dv_wres</span><span class='hljl-p'>)</span><span class='hljl-t'>
</span><span class='hljl-k'>end</span><span class='hljl-t'>

</span>
</pre>

```
```@raw html

<div style="display:inline-block">
    <p style="display:inline-block; text-align: center">
        <img src="https://gallery.pumas.ai/grouped_cwres_vs_ivar/media/image.png" alt="">

    </p>
</div>

<div style="display:inline-block">
    <p style="display:inline-block; text-align: center">
        <img src="https://gallery.pumas.ai/grouped_cwres_vs_ivar/media/image.svg" alt="">

    </p>
</div>

```
