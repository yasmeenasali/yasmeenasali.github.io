---
layout: about
description: >
   Personal jekyll website 
last_modified_at: 2023-08-14
hide_description: true
no_link_title: false 
no_excerpt: false 
hide_image: false
cover: true
---
<!-- <script type="text/javascript">
	document.getElementsByClassName("page-title")[0].classList.add("sr-only");
</script> -->

<style type="text/css">
	.page-title {
		position: absolute;
		width: 1px;
  		height: 1px;
  		margin: -1px;
  		border: 0;
  		padding: 0;
  		clip: rect(0 0 0 0);
  		overflow: hidden;
	}
</style>

<h1 id="about">About Me</h1>

<!--author-->

I have previously worked on two other projects: evaluating the stellar membership of Willman 1, a dwarf Milky Way satellite, with Professor Marla Geha; and using machine learning and multi-wavelength photometry to classify AGN with Professor Meg Urry. I graduated from Columbia University in 2020 with a BA in Astrophysics and Departmental Honors in Physics. As an undergraduate, I was a member of LIGO and I worked with Professor Szabi Marka and Dr. Zsuzsa Marka on a number of projects. I contributed to the LLAMA pipeline to search for gravitational wave and high energy neutrino coincidences, and I worked on both the software and hardware of the LIGO timing diagnostic system. As part of the University of Florida International REU program, I worked with Professor Chris Van Den Broeck at Nikhef in the testing GR subgroup of the LIGO - Virgo Collaboration. I was also a participant in the Columbia Astronomy research exchange program with Pontificia Universidad Católica de Chile, where I spent a summer working on dark matter annihilation using simulated CTA data with Dr. German Gomez-Vargas.

I care deeply about mentoring, pedagogy, and public education, and I devote time to building community in a variety of ways. I serve as an elected representative on the Astronomy Student Council at Yale, and am a member of the Astronomy Climate and Diversity Committee. I am also a McDougal Graduate Teaching Fellow at the Poorvu Center for Teaching and Learning and a Graduate Affiliate at Ezra Stiles College. Outside of astronomy, I love to care for my constantly growing collection of plants. I enjoy visiting museums and learning about art history, and I love to travel. I am also a big fan of sudoku and sudoku variants, and I often (try to) solve the puzzles from the Cracking the Cryptic youtube channel.

I was interviewed by the Blue and White maganzine in early 2020, and the illustration on the right comes from that article. You can check it out here to read more about me!

<!-- <hr style="border:2px solid gray"> -->
<hr/>
<h1 id="research">Research</h1>

I work with the SAGA Survey, a spectroscopic galaxy redshift survey aiming to characterize satellites around 100 Milky Way (MW) analog systems. As an undergraduate, I was a member of the LIGO Collaboration. You can find summaries of my work on [this page](/pages/undergrad-research). 

You can view my publications at the following links: 

<div class="body-social sidebar-social">
  <ul>
    <li> <a href="https://ui.adsabs.harvard.edu/search/q=orcid%3A0000-0002-8320-2198&sort=date%20desc%2C%20bibcode%20desc&p_=0" title="NASA ADS" class="no-mark-external" target="_blank"> <span class="icon-ads"></span> <span aria-hidden="true">NASA ADS </span><span class="sr-only">Yasmeen Asali's NASA ADS page</span></a></li>
    <li> <a href="https://scholar.google.com/citations?user=kJDwjWkAAAAJ&hl=en" title="Google Scholar" class="no-mark-external" target="_blank"> <span class="icon-googlescholar"></span> <span aria-hidden="true">Google Scholar </span><span class="sr-only">Yasmeen Asali's Google Scholar page</span></a></li>
    <li> <a href="https://orcid.org/0000-0002-8320-2198" title="ORCID" class="no-mark-external" target="_blank"> <span class="icon-orcid"></span> <span aria-hidden="true">ORCID </span><span class="sr-only">Yasmeen Asali's ORCID page</span></a></li>
  </ul>
</div>

<h2>Star Formation Histories of SAGA Satellites</h2> 
Proposed quenching mechanisms including gas starvation or strangulation, tidal stripping, or ram pressure stripping operate on different timescales as a function of stellar mass. Star formation histories (SFHs) can provide constraints on how long a galaxy has been quenched or how long it takes to transition from star forming to quiescent. Additionally, there is a known dichotomy between quenched Local Group dwarf satellites and star forming isolated dwarf galaxies. This implied transition from star forming in isolation to quenched as a satellite is indicative of a strong environmental dependence on quenching, and a rapid transition from star forming to quiescent upon infall. I work with the Prospector SED fitting software to investigate the SFHs of SAGA satellites and effect of environment.

<h2>Dwarf Galaxy Dynamical Masses</h2> 
Coming soon. 


<hr/>
<h1 id="community">Community</h1>

{% include features.md %}



<style type="text/css">
  .body-social > ul {
    display: inline-block;
    list-style-type: none;
    margin-bottom: 0;
    overflow: hidden;
    padding: 0;
  }

  .body-social > ul > li {
    float: left;
    
    /* padding-left: 5px; */
    padding-right: 10px;
    
    /* display: inline-block; */
  }


  .body-social > ul > li > a {
    display: inline;
    text-align: center;
    font-size: 0.95rem;
    font-weight: 600;
    /*width: 3rem;*/
    /*height: 4rem;*/
    padding: 4px;
    
    /* line-height: 3rem; */
    
    text-decoration: none;
    border-width: 1px;
    border-style: solid;
    border-radius: 5px;
    transition: background-color 250ms, color 250ms, text-decoration-color 250ms, border-color 250ms;
    
    /* border-bottom: none; */
  }

  .body-social > ul > li > a:not(.btn):not(.no-hover) {
    border-color: var(--accent-color);
  }

  .body-social > ul > li > a:hover {
    color: white;
    background-color: var(--accent-color);
    border-radius: 5px;
    padding: 4px;
    transition: background-color 250ms, color 250ms, text-decoration-color 250ms, border-color 250ms;
  }
</style>

[features]: #features