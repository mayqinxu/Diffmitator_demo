---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home
---

The performance of Diffmitator in the task of audio continuation. The first 2.5 seconds consist of reference content, while the subsequent 7.5 seconds contain the continuation content.

<table>
	<tr>
		<th>Text Prompt</th>
		<th>Reference</th>
		<th>Diffmitator-vanilla</th>
		<th>Diffmitator-C-Copaint</th>
	</tr>
	<tr>
		<td>A church bell ringing repeatedly.</td>
		<td>
			<audio controls>
  				<source src="demos/audio/bbc_church_bell_1_16khz_mono_ref.wav" type="audio/wav">
			</audio>
		</td>
		<td>
			<audio controls>
  				<source src="demos/audio/bbc_church_bell_1_tangosAC_25s_htsat_vanilla.wav" type="audio/wav">
			</audio>
		</td>
		<td>
			<audio controls>
  				<source src="demos/audio/bbc_church_bell_1_tangosAC_25s_htsat_copaint.wav" type="audio/wav">
			</audio>
		</td>
	</tr>
	<tr>
		<td>A bird is singing.</td>
		<td>
			<audio controls>
  				<source src="demos/audio/bbcsfx_birds_2_16khz_mono_ref.wav" type="audio/wav">
			</audio>
		</td>
		<td>
			<audio controls>
  				<source src="demos/audio/bbcsfx_birds_2_16khz_mono_tangosAC_htsat_vanilla.wav" type="audio/wav">
			</audio>
		</td>
		<td>
			<audio controls>
  				<source src="demos/audio/bbcsfx_birds_2_16khz_mono_tangosAC_htsat_copaint.wav" type="audio/wav">
			</audio>
		</td>
	</tr>
	<tr>
		<td>A dog is barking.</td>
		<td>
			<audio controls>
  				<source src="demos/audio/bbcsfx_dog_barking_16khz_mono_ref.wav" type="audio/wav">
			</audio>
		</td>
		<td>
			<audio controls>
  				<source src="demos/audio/bbcsfx_dog_barking_tangosAC_25s_htsat_vanilla.wav" type="audio/wav">
			</audio>
		</td>
		<td>
			<audio controls>
  				<source src="demos/audio/bbcsfx_dog_barking_tangosAC_25s_htsat_copaint.wav" type="audio/wav">
			</audio>
		</td>
	</tr>
	<tr>
		<td>Persian cat meowing.</td>
		<td>
			<audio controls>
  				<source src="demos/audio/cat_meowing_16khz_mono_ref.wav" type="audio/wav">
			</audio>
		</td>
		<td>
			<audio controls>
  				<source src="demos/audio/cat_meowing_tangosAC_25s_htsat_vanilla.wav" type="audio/wav">
			</audio>
		</td>
		<td>
			<audio controls>
  				<source src="demos/audio/cat_meowing_tangosAC_25s_htsat_copaint.wav" type="audio/wav">
			</audio>
		</td>
	</tr>
	<tr>
		<td>Tick-tocking by a clock.</td>
		<td>
			<audio controls>
  				<source src="demos/audio/clock_16khz_mono_ref.wav" type="audio/wav">
			</audio>
		</td>
		<td>
			<audio controls>
  				<source src="demos/audio/clock_vanilla.wav" type="audio/wav">
			</audio>
		</td>
		<td>
			<audio controls>
  				<source src="demos/audio/clock_copaint.wav" type="audio/wav">
			</audio>
		</td>
	</tr>

</table>
