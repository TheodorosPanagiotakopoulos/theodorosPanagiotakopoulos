# Welcome to My GitHub

<div id="writing"></div>

<script>
  const text = `Hi there! 👋

I am a PhD Candidate pursuing my PhD in Computational Material Science at the University of Central Florida, specializing in developing Machine Learning algorithms for nanotechnology and material design.

I worked at ASML Silicon Valley as a Modeling Product Engineer Intern, where I developed computational methods for photomask optimization and optimized simulation processes for pre-silicon fabrication to enhance efficiency.

My PhD research focuses on developing Deep Learning Classifiers and Neural Networks for molecular dynamics and kinetic Monte Carlo simulations, enhancing simulations for semiconductor fabrication processes and epitaxial metal growth on semiconductors.

I am also modeling the CO2 reduction reaction in the presence of metallic and non-metallic cations, simulating cathodes and developing voltage-stabilizing algorithms, showing that HCOO⁻ forms best via direct hydrogenation and CO via proton shuttling, overturning previous assumptions.

I have worked as a teaching assistant at the University of Central Florida, teaching electrodynamics at both the graduate and undergraduate levels.

I hold a Master's degree in Physics from the University of Central Florida, focused on computational material design, and a Master's degree from the National and Kapodistrian University of Athens, with a focus on computational physics.`;

  let index = 0;

  function type() {
    if (index < text.length) {
      document.getElementById("writing").innerHTML += text.charAt(index);
      index++;
      setTimeout(type, 50); // Adjust typing speed here
    }
  }

  type();
</script>

