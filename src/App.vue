<template lang="pug">

	#app.flex.container

		vue-particles(
			color="#555"
			:particleOpacity="0.2"
			:particlesNumber="100"
			shapeType="circle"
			:particleSize="3"
			linesColor="#333"
			:linesWidth="1"
			:lineLinked="false"
			:lineOpacity="0.1"
			:linesDistance="150"
			:moveSpeed="3"
			:hoverEffect="true"
			hoverMode="grab"
			:clickEffect="true"
			clickMode="push"
		)

		heading

		section.main.flex.container

			.column.flex

				.group.flex
					.row.flex
						input
					.row.flex
						input
				.group.flex
					.row.flex
						input
					.row.flex
						input
				.group.flex
					.row.flex
						input
					.row.flex
						input
				.group.flex
					.row.flex
						input
					.row.flex
						input

			.column.flex
				.group.flex
					.row.flex
						input
					.row.flex
						input
				.group.flex
					.row.flex
						input
					.row.flex
						input

			.column.flex
				.group.flex
					.row.flex
						input
					.row.flex
						input

			.column.flex
				.row.flex
					input

</template>

<script>

import heading from "./components/heading";

export default {
	name: "App",
	components: {
		heading
	},

}

</script>

<style src="./assets/styl/App.styl" lang="stylus"></style>
