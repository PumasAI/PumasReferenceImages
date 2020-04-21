## Etacov with kwargs

```@raw html
<pre class='hljl'>
<span class='hljl-k'>using</span><span class='hljl-t'> </span><span class='hljl-n'>Pumas</span><span class='hljl-p'>,</span><span class='hljl-t'> </span><span class='hljl-n'>PumasPlots</span><span class='hljl-p'>,</span><span class='hljl-t'> </span><span class='hljl-n'>StatsPlots</span><span class='hljl-t'>
</span><span class='hljl-nf'>include</span><span class='hljl-p'>(</span><span class='hljl-s'>&quot;model.jl&quot;</span><span class='hljl-p'>)</span><span class='hljl-t'>

</span><span class='hljl-k'>using</span><span class='hljl-t'> </span><span class='hljl-n'>Pumas</span><span class='hljl-t'> </span><span class='hljl-n'>PumasPlots</span><span class='hljl-t'>

</span><span class='hljl-s'>&quot;Here, `res` is a FittedPumasModel.&quot;</span><span class='hljl-t'>

</span><span class='hljl-nf'>etacov</span><span class='hljl-p'>(</span><span class='hljl-t'>
    </span><span class='hljl-cs'># the FPM to plot</span><span class='hljl-t'>
    </span><span class='hljl-n'>res</span><span class='hljl-p'>;</span><span class='hljl-t'>
    </span><span class='hljl-cs'># catmap shows which covariates are categorical (true)</span><span class='hljl-t'>
    </span><span class='hljl-n'>catmap</span><span class='hljl-t'> </span><span class='hljl-oB'>=</span><span class='hljl-t'> </span><span class='hljl-p'>(</span><span class='hljl-n'>isPM</span><span class='hljl-t'> </span><span class='hljl-oB'>=</span><span class='hljl-t'> </span><span class='hljl-kc'>true</span><span class='hljl-p'>,</span><span class='hljl-t'> </span><span class='hljl-n'>wt</span><span class='hljl-t'> </span><span class='hljl-oB'>=</span><span class='hljl-t'> </span><span class='hljl-kc'>true</span><span class='hljl-p'>),</span><span class='hljl-t'>
    </span><span class='hljl-cs'># plot the etas 1 and 2</span><span class='hljl-t'>
    </span><span class='hljl-n'>etas</span><span class='hljl-t'> </span><span class='hljl-oB'>=</span><span class='hljl-t'> </span><span class='hljl-p'>[</span><span class='hljl-ni'>1</span><span class='hljl-p'>,</span><span class='hljl-t'> </span><span class='hljl-ni'>2</span><span class='hljl-p'>],</span><span class='hljl-t'>
    </span><span class='hljl-cs'># link the y-axes of each row together</span><span class='hljl-t'>
    </span><span class='hljl-n'>link</span><span class='hljl-t'> </span><span class='hljl-oB'>=</span><span class='hljl-t'> </span><span class='hljl-sc'>:y</span><span class='hljl-t'>
</span><span class='hljl-p'>)</span><span class='hljl-t'>

</span>
</pre>

```
```@raw html

<div style="display:inline-block">
    <p style="display:inline-block; text-align: center">
        <img src="https://gallery.pumas.ai/etacov_with_kwargs/media/image.png" alt="">

    </p>
</div>

<div style="display:inline-block">
    <p style="display:inline-block; text-align: center">
        <img src="https://gallery.pumas.ai/etacov_with_kwargs/media/image.svg" alt="">

    </p>
</div>

```
