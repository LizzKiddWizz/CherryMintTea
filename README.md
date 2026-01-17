# CherryMintTea
Building a personal website for project hosting

To Do:
[X] Figure out how to get github page to work
[X] Add Projector Asset to template
[X] Create Friend Profile Templates
[-] Finish Home Page
    [] Add images
[-] Finish Projects Page
    [] Add images
[-] Finish Affiliations Page
    [] Add images
[-] Finish Friend Profiles
    [] Get info and assets from friends
        [] Abyss
        [-] Aso
        [] Bell
        [X] Jaed
        [-] Sera
        [] Stein
[X] Finish FAQ
[] Create MD profile templates
    [X] Main Characters
    [X] Side Characters
    [-] Background Characters
        [X] Athalmus
        [] Ascension
            [] Ascencia
                [] Non-Combat
            [] Mortal
        [] Purgatory
            [] Mortal
                [] Non-Combat
            [] Circlean
            [] Death Brigade
                [] Light
                [] Dark
        [] Lacrimae
            [] Mortal
                [] Non-Combat
            [] Lacra
                [] Martym
                [] Sev
                [] Endi
    [] Location
    [] Sentient Species
    [] Animals
    [] Plants
[] Finish one MD profile per area
    - Athalmus
        [] Hisleschtevatkana Constanza
        [] Una Atlanta
        [] Mayim Blanka
    - Ascension
        [] Merlin Lagrange (Mortal)
        [] Adamos Serim
        [] Mildred Levier Heaven (Non-Com)
    - Purgatory
        [] Rosen Lovecraft (Circlean)
        [] BECC BSoD (DB)
        [] Magnus Aueralis (Mortal Non-Com)
        [] Lawrence 'Law' Hunstman (Mortal Com)
    - Lacrimae
        [] Alloces Aluhyde (Endi- Glacius)
        [] Halcyon Galia (Endi)
        [] Geranigor Ishtarinavani (Martym)
        [] Harlan Malaphar (Sev)
    - Living Mortals
        [] Theloden Leondir
[] Add lore pages
[] Upload Important Characters

Ideas and Notes:
Meltdown Character Compendium breaks down more simply then within
original documentation.

/Character Data
    - Birthdays
    - Ages
    - Music Playlist
    - Relationships

/Athalmus
    /NewAge
        /Lunar
            - Domains As Headings
            - Character Icons have a badge deliniating to Group
            - Star in upper Corner notes Leader, who is always listed first
            - Characters are listed alongside their group mates, in established order of groups
            - Unassigned Characters have an X badge
                - Black means it is canonical
                - Red means it hasn't been decided yet
        /Tyres
        /Wednas
        /Thurst
        /Fresno
        /Helio
        /Saturn
        /Unassigned
    /Placeholder
/Arcana
    /Ataraxia
        /Ascension
            - Choir Ranks as Headings
            - Badge denotes if someone is mortal
            - If living, badge is different variation
        /Purgatory
            - Headings: Circleans, Mortals, Death Brigade
            - Badge denotes if someone is a living mortal
            - Other badges signify Rank + DB role
        /Lacrimae
            - Headings: Descendus, Obsevus, Mortal
            - Badge denotes if someone is a living mortal
            - Other badges signify Rank
                - <img class="cc-icon" src="images/icons/crown.svg">
            - Special Border for Glacius Rex with their rank # in the top left corner
                - <a class="cc-card is-special" href="...">...</a>
    /Other Arcana
/Living Mortals

For folders with subcategories;
Replace-
<a class="vault-hub-card cc-card-row" href="Hildeneth/Hilde.html">
                        <img src="../images/vault/lore.jpg" alt="Hildeneth">
                        <div class="vault-hub-overlay">
                            <div class="vault-hub-text">
                                <h3>Hildeneth</h3>
                                <p>Featured in; Gods Bleed, Tempest Testament</p>
                            </div>
                        </div>
                    </a>
With-
<div class="cc-cat">

  <!-- Header card: looks like your landing card row -->
  <div class="vault-hub-card cc-card-row cc-cat-toggle" role="button" tabindex="0" aria-expanded="false">
    <img src="../images/vault/characters.jpg" alt="Athalmus">
    <div class="vault-hub-overlay">
      <div class="vault-hub-text">
        <h3>Athalmus</h3>
        <p>Click to open options</p>
      </div>

      <span class="cc-caret" aria-hidden="true">▾</span>
    </div>
  </div>

  <!-- Panel: inside link cards (4 per row) -->
  <div class="cc-cat-panel">
    <div class="cc-inner-grid">

      <a class="vault-hub-card cc-inner-card" href="Meltdown/characters/page1.html">
        <img src="../images/vault/characters.jpg" alt="Characters">
        <div class="vault-hub-overlay">
          <div class="vault-hub-text">
            <h3>Characters</h3>
            <p>Browse profiles</p>
          </div>
        </div>
      </a>

      <a class="vault-hub-card cc-inner-card" href="Meltdown/lore/page1.html">
        <img src="../images/vault/lore.jpg" alt="Lore Pages">
        <div class="vault-hub-overlay">
          <div class="vault-hub-text">
            <h3>Lore Pages</h3>
            <p>Read entries</p>
          </div>
        </div>
      </a>

      <a class="vault-hub-card cc-inner-card" href="Meltdown/glossary.html">
        <img src="../images/vault/systems.jpg" alt="Glossary">
        <div class="vault-hub-overlay">
          <div class="vault-hub-text">
            <h3>Glossary</h3>
            <p>Terms & names</p>
          </div>
        </div>
      </a>

      <a class="vault-hub-card cc-inner-card" href="Meltdown/map.html">
        <img src="../images/vault/realms.jpg" alt="Locations">
        <div class="vault-hub-overlay">
          <div class="vault-hub-text">
            <h3>Locations</h3>
            <p>Regions & maps</p>
          </div>
        </div>
      </a>

    </div>
  </div>

</div>

Card Example:
<!-- CARD -->
                    <a class="cc-card is-special" href="characters/your-character.html">
                        <div class="cc-media">
                            <img class="cc-img" src="images/characters/char1.jpg" alt="Character Name">
                            <!-- corner icon (optional) -->
                            <!-- Image -->
                            <img class="cc-imgico" src="images/icons/star.svg" alt="" aria-hidden="true">
                            <!-- Icon -->
                            <i class="cc-icon fa-solid fa-star"></i>
                        </div>

                        <div class="cc-body">
                            <h4 class="cc-name">Character Name</h4>
                            <p class="cc-sub">Short descriptor / role</p>

                            <!-- badges bottom-right -->
                            <div class="cc-badges">
                                <span class="cc-badge badge-main">Core</span>
                                <span class="cc-badge badge-danger">Boss</span>
                                <span class="cc-badge badge-accent">Myth</span>
                                <span class="cc-badge badge-muted">WIP</span>
                            </div>
                        </div>
                    </a>


Meltdown Glossary:
✨ This denotes if it is a new addition

/Encyclopedia
    /Ataraxia
        /Arcana
            /Ascension
                - Cities
                - City Structure
                - Ministries And Segments
                - The Choir
            /Purgatory
                - Circles
                - Circle Structure
                - Death Brigade Hierarchy
                - Death Brigade Registrar (Partners and Groups)
                - Departments
            /Lacrimae
                - Houses
                - Lacrimaic Hierarchy
                - Levels of Mortis
                - Mortis Resonance
                - Vassals of Lacris
                - Vassal and Level Structure
            /The Natural Order
                - Circulum
                - Of Virtue and of Sin
                - Glacius Rex
                - Traits of the Fallen
        /Culture
            /Historia
                - Ages
                /Ascension
                /Purgatory
                /Lacrimaic
                    - Primordius (Drif)
                    - The Great Rupture
                    - Floe
            /Form
                - Food
                - Registered Weapons
            /Function
                /Known Groups
                    - House of Limbo: Lemegeton
                - Adresses
                - Education
                - Names
                - Time
        /Species
            /Cores
                - Angel
                - Devil
                - Reaper
            /Ascension Fauna
                - 
            /Purgatory Fauna
                -
            /Lacrimae
                /Lacran Subspecies
                    -
                /Fauna
                    -
    /NewAge
        - HQ Presidents
        - Department Information
    /The Enumerable
        - Dictionary
/Magic System
    - Contracts And Pacts
    - Elements
    - Power Measurement
    - Souls
/Structures
    /Locations
        - Moonlit Nebula
