<!-- File: secondRoute.svelte -->
<script lang="ts">
	// Import necessary components and icons
	import Section from '$lib/components/Section.svelte';
	import book from 'svelte-awesome/icons/book';
	import cogs from 'svelte-awesome/icons/cogs';
  </script>
  
  <div class="second-route">
	<a href="/"><h2>About Biology</h2></a>
	<p>
	  Biology is the scientific study of life and living organisms. It encompasses various sub-disciplines,
	  including molecular biology, cell biology, genetics, ecology, and more. The field of biology explores
	  the structure, function, evolution, and interactions of living organisms at different levels of organization.
	</p>
  
	<Section iconData={book} title="Branches of Biology">
	  <ul>
		<li>Molecular Biology</li>
		<li>Cell Biology</li>
		<li>Genetics</li>
		<li>Ecology</li>
		<li>Evolutionary Biology</li>
		<li>Botany</li>
		<li>Zoology</li>
		<li>Microbiology</li>
		<li>Physiology</li>
		<li>Biotechnology</li>
	  </ul>
	</Section>
  
	<Section iconData={cogs} title="Importance of Biology">
	  <p>
		Biology plays a crucial role in our understanding of life, health, and the natural world. It helps us
		comprehend the complex mechanisms within cells, uncover the genetic basis of diseases, study ecosystems,
		and develop innovations in medicine, agriculture, and conservation. By studying biology, we gain insights
		into the diversity and interconnectedness of life forms on our planet.
	  </p>
	</Section>
  </div>
  
  <style>
	/* CSS styles for the second route */
	.second-route {
	  max-width: 800px;
	  margin: 0 auto;
	  padding: 40px;
	  background-color: #fcfcbb;
	  border-radius: 8px;
	  box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
	}
  
	h2 {
	  font-size: 24px;
	  font-weight: bold;
	  margin-bottom: 20px;
	}
  
	p {
	  line-height: 1.5;
	  margin-bottom: 20px;
	}
  
	ul {
	  list-style-type: disc;
	  margin-left: 20px;
	  margin-bottom: 20px;
	}
  
	li {
	  margin-bottom: 10px;
	}
  
	/* Styles for the Section component */
	.section {
	  margin-bottom: 40px;
	}
  
	.section-title {
	  display: flex;
	  align-items: center;
	  font-weight: bold;
	  margin-bottom: 20px;
	}
  
	.section-icon {
	  width: 24px;
	  height: 24px;
	  margin-right: 10px;
	}
  
	.section-content {
	  line-height: 1.5;
	}
  </style>
  