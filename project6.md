# Intro to Game programming
The games below are the class project of GSAS-2540 Intro to Game Programming at RPI.\
All of the games were programmed in unity with C#.\
These games are made on a solo team.\
Please use the tabs below to try each game!

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

  padding: 0.5rem;

  background: #267CB9;
  color: #fff;

  cursor: pointer;

  border-radius: 5px;
  transition: all 0.25s ease-out;

}

.lbl-toggle:hover {
  color: #ccc;
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
  <input id="collapsible3" class="toggle" type="checkbox">
  <label for="collapsible3" class="lbl-toggle">Platformer</label>
  <div class="collapsible-content">
    <div class="content-inner">
      <p>This game is a platformer game. The player needs to overcome the barriers and reach the goal on the right.</p>
      <strong>Control method:</strong>
       <p>WASD or ↑↓←→ for direction, space for jump. Hold space on the wall to climb up.</p>
      <iframe frameborder="0" src="https://itch.io/embed-upload/2622018?color=333333" allowfullscreen="" width="450" height="350"><a href="https://moritomo.itch.io/platformer">Play Platformer on itch.io</a></iframe>
      <p><strong>Note:</strong>Full screen for best experience</p>
    </div>
  </div>
</div>
<p style="margin-bottom: 5px;"></p>

<div class="wrap-collabsible">
  <input id="collapsible4" class="toggle" type="checkbox">
  <label for="collapsible4" class="lbl-toggle">Shump</label>
  <div class="collapsible-content">
    <div class="content-inner">
      <p style="margin: 0px;">Shump (Shoot them up) is a shooting game. Players has to use the weapon to protect themselves from the evil robots.</p>
      <strong>Control method:</strong>
       <p>WASD or ↑↓←→ for direction, left button to shoot.</p>
      <iframe frameborder="0" src="https://itch.io/embed-upload/2620863?color=333333" allowfullscreen="" width="450" height="350"><a href="https://moritomo.itch.io/shump">Play Shump on itch.io</a></iframe>
      <p><strong>Note:</strong>Full screen for best experience</p>
    </div>
  </div>
</div>
<p style="margin-bottom: 5px;"></p>
