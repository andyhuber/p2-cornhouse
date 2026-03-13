<script>(function(){function init(){if(location.search.includes('teach')){document.body.classList.add('teach-mode')}document.querySelectorAll('input[type=checkbox]').forEach(function(c){c.removeAttribute('disabled')});if(!document.getElementById('teach-toggle')){var btn=document.createElement('button');btn.id='teach-toggle';btn.textContent=document.body.classList.contains('teach-mode')?'📖 Plan':'📋 Teach';btn.onclick=function(){document.body.classList.toggle('teach-mode');btn.textContent=document.body.classList.contains('teach-mode')?'📖 Plan':'📋 Teach'};document.body.appendChild(btn)}}if(document.readyState==='loading'){document.addEventListener('DOMContentLoaded',init)}else{setTimeout(init,200)}new MutationObserver(function(){document.querySelectorAll('input[type=checkbox][disabled]').forEach(function(c){c.removeAttribute('disabled')})}).observe(document.body,{childList:true,subtree:true})})();</script>

# 📅 P2 Praktikum — Wochenplanung

<div class="dashboard">

<div class="day-row">
<div class="day-label">Mo 23.3</div>
<div class="day-cards">
<a class="card card-nmg" href="23.3+-+NMG+-+Explorationspräsentation">🔬 NMG<br/><span>Explorationspräsentation</span></a>
<a class="card card-bg" href="23.3+-+BE+-+Mein+Angstmonster+%26+Mutfigur">🎨 BG<br/><span>Angstmonster & Mutfigur</span></a>
</div>
</div>

<div class="day-row">
<div class="day-label">Di 24.3</div>
<div class="day-cards">
<a class="card card-de" href="24.3+-+De+-+Viel+zu+hoch">📖 De<br/><span>Viel zu hoch</span></a>
<a class="card card-ma" href="24.3+-+Ma+-+3.+Kl+-+Rechenstrategie+Subtraktion">🔢 Ma 3.Kl<br/><span>Rechenstrategie Subtraktion</span></a>
<a class="card card-nmg" href="24.3+-+NMG+-+Weizenpflanzen">🔬 NMG<br/><span>Weizenpflanzen</span></a>
</div>
</div>

<div class="day-row">
<div class="day-label">Mi 25.3</div>
<div class="day-cards">
<a class="card card-ma" href="25.3+-+Ma+-+4.+Kl+-+Schriftliche+Subtraktion">🔢 Ma 4.Kl<br/><span>Schriftliche Subtraktion</span></a>
</div>
</div>

<div class="day-row">
<div class="day-label">Do 26.3</div>
<div class="day-cards">
<a class="card card-nmg" href="26.3+-+NMG+-+Welche+Getreide+gibt+es%3F">🔬 NMG<br/><span>Welche Getreide gibt es?</span></a>
</div>
</div>

<div class="day-row">
<div class="day-label">Fr 27.3</div>
<div class="day-cards">
<a class="card card-en" href="27.3+-+En+-+Trees+are+important">🌍 En<br/><span>Trees are important</span></a>
</div>
</div>

</div>
