---
layout: page
title: Osobné záujmy
permalink: /interests/
---

Z mojich osobných záujmov by som chcel určite spomenúť šport, aktívny aj pasívny. Rád si zahrajem futbal alebo volejbal aktívne, alebo si
pozriem futbal v anglickej a španielskej lige alebo ligu majstrov v televízii. 
V nasledujúcej tabuľke sú športovci, ktorých som vždy obdivoval a patria medzi mojich obľúbených športovcov.

<div class="schools">
		<table style="width:70%" align="center">
			<tr>
				<th>Šport</th>
				<th>Meno</th>
				<th>Štát</th>
			</tr>
			{% for sportsman in site.data.sports %}
			<tr>
				<td>{{sportsman.sport}}</td>
				<td>{{sportsman.meno}}</td> 
				<td>{{sportsman.stat}}</td> 
			</tr>
			{% endfor %}
		</table>
</div>



