# Intro to Game programming
<style>
.wrap-collabsible {
  margin-bottom: 1.2rem 0;
}

input[type='checkbox'] {
  display: none;
}

.lbl-toggle {
  display: block;

  font-weight: bold;
  font-family: monospace;
  font-size: 1.2rem;
  text-transform: uppercase;
  text-align: center;

  padding: 1rem;

  background: #888;
  color: #eee;

  cursor: pointer;

  border-style: solid;
  border-radius: 5px;
  transition: all 0.25s ease-out;

}

.lbl-toggle:hover {
  color: #333;
}

.lbl-toggle::before {
  content: ' ';
  display: inline-block;

  border-top: 5px solid transparent;
  border-bottom: 5px solid transparent;
  border-left: 5px solid currentColor;
  vertical-align: middle;
  margin-right: .7rem;
  transform: translateY(-2px);

  transition: transform .2s ease-out;
}

.toggle:checked + .lbl-toggle::before {
  transform: rotate(90deg) translateX(-3px);
}

.collapsible-content {
  max-height: 0px;
  overflow: hidden;
  transition: max-height .25s ease-in-out;
}

.toggle:checked + .lbl-toggle + .collapsible-content {
  max-height: 100vh;
}

.toggle:checked + .lbl-toggle {
  border-bottom-right-radius: 0;
  border-bottom-left-radius: 0;
}

.collapsible-content .content-inner {
  background: rgba(60, 60, 60, .2);
  border-bottom: 1px solid rgba(60, 60, 60, .45);
  border-bottom-left-radius: 7px;
  border-bottom-right-radius: 7px;
  padding: .5rem 1rem;
}
</style>

<div class="wrap-collabsible">
  <input id="collapsible1" class="toggle" type="checkbox">
  <label for="collapsible1" class="lbl-toggle">Adventure</label>
  <div class="collapsible-content">
    <div class="content-inner">
    <iframe frameborder="0" src="https://itch.io/embed/735139" width="100%" height="150"><a href="https://moritomo.itch.io/adventure">Adventure by Moritomo</a></iframe>
    </div>
  </div>
</div>
<p style="margin-bottom: 5px;"></p>

<div class="wrap-collabsible" margin>
  <input id="collapsible2" class="toggle" type="checkbox">
  <label for="collapsible2" class="lbl-toggle">Apple Picker</label>
  <div class="collapsible-content">
    <div class="content-inner">
    <iframe frameborder="0" src="https://itch.io/embed/735145" width="450" height="150"><a href="https://moritomo.itch.io/applepicker">ApplePicker by Moritomo</a></iframe>
    </div>
  </div>
</div>

<div class="wrap-collabsible">
  <input id="collapsible3" class="toggle" type="checkbox">
  <label for="collapsible3" class="lbl-toggle">Platformer</label>
  <div class="collapsible-content">
    <div class="content-inner">
      <iframe frameborder="0" src="https://itch.io/embed/734509" width="450" height="150"><a href="https://moritomo.itch.io/platformer">Platformer by Moritomo</a></iframe>
    </div>
  </div>
</div>

<div class="wrap-collabsible">
  <input id="collapsible4" class="toggle" type="checkbox">
  <label for="collapsible4" class="lbl-toggle">Shump</label>
  <div class="collapsible-content">
    <div class="content-inner">
      <p style="margin: 0px;">Shump (Shoot them up) is a shooting game.</p>
      <iframe frameborder="0" src="https://itch.io/embed/735154?linkback=true" width="450" height="150"><a href="https://moritomo.itch.io/shump">Shump by Moritomo</a></iframe>
    </div>
  </div>
</div>
