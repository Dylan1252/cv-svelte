<script lang="ts">
	import Section from '$lib/components/Section.svelte';
	import book from 'svelte-awesome/icons/book';
	import briefcase from 'svelte-awesome/icons/briefcase';
	import cogs from 'svelte-awesome/icons/cogs';
	import user from 'svelte-awesome/icons/user';
</script>

<div class="readable-area">
	<a class="header" href="/secondRoute">
		<div class="header-text">
			<h1>Biology</h1>
			<p>The Study of Life</p>
		</div>
		<img
			alt="biology icon"
			class="avatar"
			src="https://cdn-icons-png.flaticon.com/512/2784/2784428.png"
		/>
	</a>

	<div class="content">
		<Section iconData={user} title="Profile">
			<p>
				Biology is the scientific study of life and living organisms. It encompasses various sub-disciplines,
				including molecular biology, cell biology, genetics, ecology, and more. The field of biology explores
				the structure, function, evolution, and interactions of living organisms at different levels of organization.
				Biology plays a crucial role in our understanding of life, health, and the natural world. It helps us
				comprehend the complex mechanisms within cells, uncover the genetic basis of diseases, study ecosystems,
				and develop innovations in medicine, agriculture, and conservation. By studying biology, we gain insights
				into the diversity and interconnectedness of life forms on our planet.
			</p>
		</Section>
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
		<Section iconData={briefcase} title="Importance of Biology">
			<p>
				Biology plays a crucial role in our understanding of life, health, and the natural world. It helps us
				comprehend the complex mechanisms within cells, uncover the genetic basis of diseases, study ecosystems,
				and develop innovations in medicine, agriculture, and conservation. By studying biology, we gain insights
				into the diversity and interconnectedness of life forms on our planet.
			</p>
		</Section>
		<Section iconData={cogs} title="Uses">
			<ul>
				<li>Scientific Research</li>
				<li>Data Analysis</li>
				<li>Lab Techniques</li>
			</ul>
		</Section>
	</div>
</div>

<style>
	/* CSS styles for the biology page */
	.readable-area {
		display: flex;
		flex-direction: column;
		background-color: #fcfcbb;
		padding: 5px;
	}

	.header {
		padding: 16px;
		display: flex;
		flex-direction: column-reverse;
		align-items: center;
		border-bottom: 2px solid black;
		text-decoration: none;
		color: #000000;
	}

	.header-text {
		text-align: center;
		flex: 1;
		margin-right: 16px;
	}

	h1 {
		font-family: 'peralta';
	}

	.avatar {
		width: 128px;
		height: 128px;
		border: 4px solid #000000;
		border-radius: 100%;
	}

	.content {
		display: grid;
		grid-template-columns: repeat(1, minmax(0, 1fr));
		gap: 32px;
		padding: 32px;
	}

	ul {
		list-style-type: none;
		margin-left: 0;
		padding-left: 0;
	}

	li {
		display: flex;
		flex-direction: row;
		align-items: center;
		justify-content: space-between;
	}

	li span {
		margin-right: 16px;
	}

	.gauge {
		display: flex;
		flex-direction: row;
	}

	.bullet {
		border-radius: 100%;
		width: 16px;
		height: 16px;
		margin: 4px;
		background-color: #f0eeda;
	}

	.filled-bullet {
		background-color: #F9FBE7;
	}

	
</style>
