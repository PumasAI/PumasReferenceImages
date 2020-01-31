## Correlation plot

```@raw html
<pre class='hljl'>
<span class='hljl-nf'>include</span><span class='hljl-p'>(</span><span class='hljl-s'>&quot;model.jl&quot;</span><span class='hljl-p'>)</span><span class='hljl-t'>
 </span><span class='hljl-s'>&quot;Here, `res` is a FittedPumasModel.&quot;</span><span class='hljl-t'>

 </span><span class='hljl-nf'>corrplot</span><span class='hljl-p'>(</span><span class='hljl-nf'>empirical_bayes</span><span class='hljl-p'>(</span><span class='hljl-n'>res</span><span class='hljl-p'>);</span><span class='hljl-t'> </span><span class='hljl-n'>label</span><span class='hljl-t'> </span><span class='hljl-oB'>=</span><span class='hljl-t'> </span><span class='hljl-p'>[</span><span class='hljl-sc'>:eta_1</span><span class='hljl-p'>,</span><span class='hljl-t'> </span><span class='hljl-sc'>:eta_2</span><span class='hljl-p'>])</span><span class='hljl-t'>

</span>
</pre>

```
```@raw html

<div style="display:inline-block">
    <p style="display:inline-block; text-align: center">
        <img src="http://pumas.ai/PumasReferenceImages/correlation_plot/media/image.png" alt="">

    </p>
</div>

<div style="display:inline-block">
    <p style="display:inline-block; text-align: center">
        <img src="http://pumas.ai/PumasReferenceImages/correlation_plot/media/image.svg" alt="">

    </p>
</div>

```
