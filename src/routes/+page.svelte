<script>
	import DCalc from "$lib/components/DCalc.svelte";
	import MotorsSetStep from "$lib/components/MotorsSetStep.svelte";
	import SpeedAccel from "$lib/components/SpeedAccel.svelte";
	import { Column, Grid, Row } from "carbon-components-svelte";
</script>

<Grid fullWidth>
	<Row noGutter>
		<Column>
			<MotorsSetStep />
		</Column>
	</Row>
	<Row noGutter>
		<Column>
			<SpeedAccel />
		</Column>
	</Row>
	<Row noGutter>
		<Column>
			<DCalc />
		</Column>
	</Row>
</Grid>
