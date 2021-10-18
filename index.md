<!-- Header -->
~~~
<div class="jumbotron jumbotron-fluid no-pad">
  <div class="container" style="text-align:center">
    <img src="/assets/logo.png" style="max-width:100%;padding-bottom:20px"  />

    <h2>The <i>Elegant</i> Machine Learning Stack</h2>
    Flux is a 100% pure-Julia stack and provides lightweight abstractions on top of Julia's native GPU
    and AD support. It makes the easy things easy while remaining fully hackable.

    <div class="buttons">
      <a class="btn btn-primary btn-lg" href="https://fluxml.ai/Flux.jl/stable/#Installation-1" role="button"><i class="fas fa-download"></i> Try It Out</a>
      <a class="btn btn-primary btn-lg" href="https://github.com/FluxML/Flux.jl" role="button" target="_blank"><i class="fas fa-star"></i> GitHub</a>
      <a class="btn btn-primary btn-lg" href="https://twitter.com/FluxML" role="button" target="_blank"><i class="fab fa-twitter"></i> Follow on Twitter</a>
    </div>
  </div>
</div>
~~~

<!-- Main Content -->

<!-- FEATURES/FEATURES -->
~~~
<div class="features" style="background:white;padding-top:2em;">
  <div class="container">
    <div class="row">
      <div class="col-md-12" style="text-align:center;color:rgb(100,130,130)">
        <h2>Features</h2>
        Flux has features that sets it apart among ML systems.
      </div>
    </div>
    <div class="row">
      <div class="col-md feature">
        <h5>Compiled Eager Code</h5>
        <p>
          Flux provides a single, intuitive way to define models, just like mathematical notation.
          Julia transparently <a href="https://julialang.org/blog/2018/12/ml-language-compiler">compiles your code</a>, optimising and fusing kernels for the GPU, for the best performance.
        </p>
      </div>

      <div class="col-md feature">
        <h5>Differentiable Programming</h5>
        <p>
          Existing Julia libraries are differentiable and can be incorporated directly into Flux models.
          Cutting edge models such as <a href="https://julialang.org/blog/2019/01/fluxdiffeq">Neural ODEs</a> are first class, and <a href="https://github.com/FluxML/Zygote.jl">Zygote</a> enables overhead-free gradients.
        </p>
      </div>

      <div class="col-md feature">
        <h5>First-class GPU support</h5>
        <p>
          GPU kernels can be written directly in Julia via <a href="https://github.com/JuliaGPU/CUDA.jl">CUDA.jl</a>.
          Flux is uniquely hackable and any part can be tweaked, from GPU code to custom gradients and layers.
        </p>
      </div>
    </div>
    <div class="row">
      <div class="col-md feature">
        <h5>The Model Zoo</h5>
        <p>
          A <a href="https://github.com/FluxML/model-zoo">rich collection</a> of Flux scripts to learn from, or tweak to your own data.
          Trained Flux models can be used from <a href="https://github.com/JuliaText/TextAnalysis.jl">TextAnalysis</a> or <a href="https://github.com/FluxML/Metalhead.jl">Metalhead</a>.
        </p>
      </div>

      <div class="col-md feature">
        <h5>TPUs & Colab</h5>
        <p>
          Flux models can be <a href="https://github.com/JuliaTPU/XLA.jl">compiled to TPUs</a> for cloud supercomputing, and run from Google Colab notebooks.
        </p>
      </div>
    </div>
  </div>
</div>
~~~

<!-- FEATURES/ECOSYSTEM -->
~~~
<div class="features" style="background:white;padding-top:2em;">
  <div class="container">
    <div class="row">
      <div class="col-md-12" style="text-align:center;color:rgb(100,130,130)">
        <h2>
          Ecosystem
          <a class="btn btn-primary btn-lg" href="/ecosystem/" role="button" style="float: right;">See all <i class="fas fa-arrow-circle-right"></i> </a>
        </h2>
        Flux has a diverse ecosystem that includes models available for reuse and other useful packages.
      </div>
    </div>
    <div class="row">

      <div class="col-md feature">
        <h5>Probabilistic Programming</h5>
        <p>
          The <a href="https://github.com/TuringLang/Turing.jl">Turing.jl</a> and <a href="https://github.com/willtebbutt/Stheno.jl">Stheno</a> libraries enable probabilistic programming, bayesian inference and Gaussian processes on top of Flux.
        </p>
      </div>

      <div class="col-md feature">
        <h5>GeometricFlux</h5>
        <p>
          <a href="https://github.com/yuehhua/GeometricFlux.jl">GeometricFlux.jl</a> is a geometric deep learning library for Flux and has support of CUDA GPU acceleration with CUDA.
        </p>
      </div>

      <div class="col-md feature">
        <h5>Metalhead</h5>
        <p>
          <a href="https://github.com/FluxML/Metalhead.jl">Metalhead</a> includes many state-of-the-art computer vision models which can easily be used for transfer learning.
        </p>
      </div>
    </div>
    <div class="row">
      <div class="col-md feature">
        <h5>SciML</h5>
        <p>
          The <a href="https://sciml.ai/">SciML</a> ecosystem uses Flux and Zygote to mix neural nets with differential equations, to get the best of black box and mechanistic modelling.
        </p>
      </div>

      <div class="col-md feature">
        <h5>Transformers</h5>
        <p>
          <a href="https://github.com/chengchingwen/Transformers.jl">Transformers.jl</a> provides components for Transformer models for NLP, as well as providing several trained models out of the box.
        </p>
      </div>

      <div class="col-md feature">
        <h5>DiffEqFlux</h5>
        <p>
          <a href="https://github.com/SciML/DiffEqFlux.jl">DiffEqFlux.jl</a> provides tools for creating Neural Differential Equations.
        </p>
      </div>
    </div>

  </div>
</div>
~~~

<!-- FEATURES / COMMUNITY -->
~~~
<div class="features" style="background:white;padding-top:2em;">
  <div class="container">
    <div class="row">
      <div class="col-md-12" style="text-align:center;color:rgb(100,130,130)">
        <h2>Community</h2>
        Get in touch with the Flux community.
      </div>
    </div>
    <div class="row">
      <div class="col-md feature">
        <h5>Community team</h5>
        <p>
          Join the <a href="https://github.com/FluxML/ML-Coordination-Tracker">group of community maintainers</a> supporting the FluxML ecosystem.
        </p>
      </div>

      <div class="col-md feature">
        <h5>Discourse forum</h5>
        <p>
          <a href="https://discourse.julialang.org/c/domain/ML/24">Machine Learning in Julia</a> community.
        </p>
      </div>

      <div class="col-md feature">
        <h5>Slack</h5>
        <p>
          <a href="https://julialang.org/slack/">Official Julia Slack</a> for casual conversation.
        </p>
      </div>

      <div class="col-md feature">
        <h5>Zulip</h5>
        <p>
          <a href="https://julialang.zulipchat.com">Zulip server</a> for the Julia programming language community.
        </p>
      </div>
    </div>
  </div>
</div>
~~~

<!-- FEATURES / WHY FLUX -->
~~~
<div class="features" style="background:white;padding-top:2em;">
  <div class="container">
    <div class="row">
      <div class="col-md-12" style="text-align:center;color:rgb(100,130,130)">
        <h2>Why Flux?</h2>
      </div>
    </div>
    <div class="row">
      <iframe width="100%" height="400" src="https://www.youtube-nocookie.com/embed/g_qstKogPYw" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
    </div>
  </div>
</div>
~~~

<!-- Friends -->
~~~
<div class="friends">
  <div class="container">
    <div class="col-md-12" style="text-align:center;color:rgb(100,130,130)">
      <h2>Researchers, users, and developers of Flux</h2>
     </div>
    <ul>
      <li><a href="https://julia.mit.edu"><img src="/assets/friends/mit-logo.png"></a></li>
      <li><a href="https://www.ucl.ac.uk"><img src="/assets/friends/ucl-logo.png"></a></li>
      <li><a href="https://www.utoronto.ca"><img src="/assets/friends/uoft_logo.png"></a></li>
      <li><a href="https://juliacomputing.com"><img src="/assets/friends/juliac-logo.png"></a></li>
      <li><a href="https://www.turing.ac.uk/research/research-projects/machine-learning-julia"><img src="/assets/friends/alan-turing.jpg"></a></li>
      <li><a href="https://www.ed.ac.uk"><img src="/assets/friends/edinburgh.png"></a></li>
      <li><a href="https://www.relational.ai"><img src="/assets/friends/rai-logo.png"></a></li>
      <li><a href="https://www.washington.edu"><img src="/assets/friends/washington.jpg"></a></li>
      <li><a href="https://www.cam.ac.uk"><img src="/assets/friends/cambridge.jpg"></a></li>
      <li><a href="https://www.cmu.edu"><img src="/assets/friends/cmu-logo.png"></a></li>
      <li><a href="https://www.invenia.ca"><img src="/assets/friends/invenia-logo.png"></a></li>
      <li><a href="https://beacon.bio"><img src="/assets/friends/beacon_biosignals.jpg"></a></li>
    </ul>
  </div>
</div>
~~~
