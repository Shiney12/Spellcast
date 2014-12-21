<?xml version="1.0" ?>
<spellcast xmlns:xi="http://www.w3.org/2001/XInclude">
    <config />
    <variables clear="True">
        <!--- Standard Variables 1 --->
        <var name="TriggerSetOne">Shackled*|Grim*|Dancing Chains|Vulcan*|Barbed*|*Schism|Carnal*</var>
        <var name="TriggerSetTwo">Poison V|Poisonga V|Scop's*|*Pastoral|*Fantasia|Raptor*</var>
        <var name="TriggerSetThree">Netherspikes|Foxfire|Diaga V|Banishga V|Goblin Gavotte</var>
        <var name="Resist">R</var>
        <var name="Area">Outside</var>
        <var name="Distance">6.5</var>
        <var name="Delay-JA">0.3</var>
        <var name="Delay-Spell">0.2</var>
        <var name="LockMain">1</var>
        <var name="R-Weapon">Trollbane</var>
        <var name="Armor-Idle">BlankSet</var>
        <var name="Armor-Engaged">BlankSet</var>
        <!--- Standard Variables 2 --->
        <var name="VAR-TP">HASTE</var>
        <var name="VAR-WS">ATT</var>
        <var name="VAR-Utsusemi">Counter</var>
        <var name="Movement-Idle">Movement</var>
        <var name="Movement-Engaged">BlankSet</var>
        <var name="EquipmentSlot-Set">PieceOfGear</var>
        <!--- Standard Variables 3 --->
        <!--- Multi-Class Variables  --->
        <var name="Berserk">N</var>
        <var name="STYLE">H2H</var>
        <!--- Specific Variables --->
        <var name="HundredFists">BlankSet</var>
        <var name="ImpetusSet">BlankSet</var>
        <var name="PerfectCounterSet">BlankSet</var>
                <var name="REar">Ethereal Earring</var>
        <!--- Include Variables --->
        <xi:include href="Akyrey_Includes.xml" xpointer="//include[@name='EleStaffConst']/*" />
    </variables>
    <sets>
        <group name="Abyssea-R">
            <set name="Idle" baseset="PDT">
			                    <ammo>Bibiki seashell</ammo>
                                <neck>Orochi Nodowa</neck>
								<head>Arh. Jinpachi +1</head>
								<back>Boxer's mantle</back>
                                <body>Arhat's Gi +1</body>
                                <hands>Bandomusha kote</hands>
                                <lring>Toreador's Ring</lring>
								<rring>Jelly Ring</rring>
                                <waist>Warwolf Belt</waist>
                                <legs>Melee Hose</legs>
                                <feet>Melee Gaiters</feet>
								<lear>Merman's Earring</lear>
                                <rear>Merman's Earring</rear>
								</set>
            <set name="Resting">
                                <neck>Orochi Nodowa</neck>
                                <body>Melee Cyclas</body>
                                <back>Melee Cape</back>
								<ammo>Bibiki seashell</ammo>
            </set>
            <set name="PDT">
                                <head></head>
								<back></back>
                                <neck></neck>
                                <body></body>
                                <hands></hands>
                                <lring></lring>
								<rring></rring>
                                <waist></waist>
                                <legs></legs>
                                <feet></feet>
            </set>
            <set name="MDT">
                                <neck></neck>
                                <lear>Merman's Earring</lear>
                                <rear>Merman's Earring</rear>
                                <lring></lring>
                                <rring></rring>
                                <back>Lamia Mantle +1</back>
            </set>
            <set name="FullEvasion">
                                <ammo></ammo>
                                <head>Walahra Turban</head>
                                <neck></neck>
                                <lear></lear>
                                <rear></rear>
                                <body></body>
                                <back></back>
                                <legs></legs>
            </set>
            <set name="Movement">
                <feet>Melee gaiters</feet>
            </set>
            <set name="BlankSet|BlankSetSet" />
            <set name="TP-H2H-ACC">
                                <ammo>Tiphia sting</ammo>
                                <head>Walahra Truban</head>
                                <neck>Peacock Amulet</neck>
                                <lear></lear>
                                <rear>Brutal Earring</rear>
                                <body>Scp. Harness +1</body>
                                <hands>bandomusha kote</hands>
                                <lring>Toreador's ring</lring>
                                <rring>Sniper's ring +1</rring>
                                <back>Amemet mantle +1</back>
                                <waist>Brown Belt</waist>
                                <legs>Melee Hose</legs>
                                <feet>Sarutobi Kyahan</feet>
            </set>
            <set name="TP-H2H-HASTE" baseset="TP-H2H-ACC">
                                <ammo>Tiphia sting</ammo>
                                <head>Walahra Truban</head>
                                <neck>Peacock Amulet</neck>
                                <lear></lear>
                                <rear>Brutal Earring</rear>
                                <body>Scp. Harness +1</body>
                                <hands>bandomusha kote</hands>
                                <lring>Toreador's ring</lring>
                                <rring>Sniper's ring +1</rring>
                                <back>Amemet mantle +1</back>
                                <waist>Brown Belt</waist>
                                <legs>Melee Hose</legs>
                                <feet>Sarutobi Kyahan</feet>            
            </set>
            <set name="TP-H2H-DEX" baseset="TP-H2H-HASTE">
                                                                <ammo>Tiphia sting</ammo>
                                <head>Walahra Truban</head>
                                <neck>Peacock Amulet</neck>
                                <lear></lear>
                                <rear>Brutal Earring</rear>
                                <body>Scp. Harness +1</body>
                                <hands>bandomusha kote</hands>
                                <lring>Toreador's ring</lring>
                                <rring>Sniper's ring +1</rring>
                                <back>Amemet mantle +1</back>
                                <waist>Brown Belt</waist>
                                <legs>Melee Hose</legs>
                                <feet>Melee gaiters</feet>
            </set>
            <set name="TP-H2H-EVA" baseset="TP-H2H-HASTE">
                                                                <ammo>Tiphia sting</ammo>
                                <head>Walahra Truban</head>
                                <neck>Peacock Amulet</neck>
                                <lear></lear>
                                <rear>Brutal Earring</rear>
                                <body>Scp. Harness +1</body>
                                <hands>bandomusha kote</hands>
                                <lring>Toreador's ring</lring>
                                <rring>Sniper's ring +1</rring>
                                <back>Amemet mantle +1</back>
                                <waist>Brown Belt</waist>
                                <legs>Melee Hose</legs>
                                <feet>Melee gaiters</feet>>
            </set>
            <set name="TP-H2H-PDT" baseset="TP-H2H-HASTE">
                                                                <ammo>Tiphia sting</ammo>
                                <head>Walahra Truban</head>
                                <neck>Peacock Amulet</neck>
                                <lear></lear>
                                <rear>Brutal Earring</rear>
                                <body>Scp. Harness +1</body>
                                <hands>bandomusha kote</hands>
                                <lring>Toreador's ring</lring>
                                <rring>Sniper's ring +1</rring>
                                <back>Amemet mantle +1</back>
                                <waist>Brown Belt</waist>
                                <legs>Melee Hose</legs>
                                <feet>Melee gaiters</feet>
            </set>
            <set name="TP-KICK-ACC">
                                                                <ammo>Tiphia sting</ammo>
                                <head>Walahra Truban</head>
                                <neck>Peacock Amulet</neck>
                                <lear></lear>
                                <rear>Brutal Earring</rear>
                                <body>Scp. Harness +1</body>
                                <hands>bandomusha kote</hands>
                                <lring>Toreador's ring</lring>
                                <rring>Sniper's ring +1</rring>
                                <back>Scp. Harness +1</back>
                                <waist>Brown Belt</waist>
                                <legs>Melee Hose</legs>
                                <feet>Seihanshi habaki</feet>
            </set>
            <set name="TP-KICK-HASTE" baseset="TP-KICK-ACC">
                                                                <ammo>Tiphia sting</ammo>
                                <head>Walahra Truban</head>
                                <neck>Peacock Amulet</neck>
                                <lear></lear>
                                <rear>Brutal Earring</rear>
                                <body>Scp. Harness +1</body>
                                <hands>bandomusha kote</hands>
                                <lring>Toreador's ring</lring>
                                <rring>Sniper's ring +1</rring>
                                <back>Amemet mantle +1</back>
                                <waist>Brown Belt</waist>
                                <legs>Melee Hose</legs>
                                <feet>Seihanshi habaki</feet>
            </set>
            <set name="TP-KICK-DEX" baseset="TP-KICK-HASTE">
			                                <ammo>Tiphia sting</ammo>
                                <head>Walahra Truban</head>
                                <neck>Peacock Amulet</neck>
                                <lear></lear>
                                <rear>Brutal Earring</rear>
                                <body>Scp. Harness +1</body>
                                <hands>bandomusha kote</hands>
                                <lring>Toreador's ring</lring>
                                <rring>Sniper's ring +1</rring>
                                <back>Amemet mantle +1</back>
                                <waist>Brown Belt</waist>
                                <legs>Melee Hose</legs>
                                <feet>Seihanshi habaki</feet>
            </set>
            <set name="TP-KICK-EVA" baseset="TP-KICK-HASTE">
                                                                <ammo>Tiphia sting</ammo>
                                <head>Walahra Truban</head>
                                <neck>Peacock Amulet</neck>
                                <lear></lear>
                                <rear>Brutal Earring</rear>
                                <body>Scp. Harness +1</body>
                                <hands>bandomusha kote</hands>
                                <lring>Toreador's ring</lring>
                                <rring>Sniper's ring +1</rring>
                                <back>Amemet mantle +1</back>
                                <waist>Brown Belt</waist>
                                <legs>Melee Hose</legs>
                                <feet>Seihanshi habaki</feet>k>
            </set>
            <set name="TP-KICK-PDT" baseset="TP-KICK-HASTE">
                                                                <ammo>Tiphia sting</ammo>
                                <head>Walahra Truban</head>
                                <neck>Peacock Amulet</neck>
                                <lear></lear>
                                <rear>Brutal Earring</rear>
                                <body>Scp. Harness +1</body>
                                <hands>bandomusha kote</hands>
                                <lring>Toreador's ring</lring>
                                <rring>Sniper's ring +1</rring>
                                <back>Amemet mantle +1</back>
                                <waist>Brown Belt</waist>
                                <legs>Melee Hose</legs>
                                <feet>Seihanshi habaki</feet>
            </set>
            <set name="Victory Smite-ACC-N">
                                <ammo>Tantra Tathlum</ammo>
                                <head>Aias Bonnet</head>
                                <neck>Rancor Collar</neck>
                                <!--<neck>Light Gorget</neck>-->
                                <lear>Brutal Earring</lear>
                                <rear>$REar</rear>
                                <body>Tantra Cyclas +2</body>
                                <hands>Heafoc Mitts</hands>
                                <lring>Epona's Ring</lring>
                                <rring>Spiral Ring</rring>
                                <back>Atheling Mantle</back>
                                <waist>Pipilaka Belt</waist>
                                <!--<legs>Shura Haidate</legs>-->
                                <legs>Byakko's Haidate</legs>
                                <feet>Tantra Gaiters +2</feet>
            </set>
            <set name="Victory Smite-ACC-Berserk" baseset="Victory Smite-ACC-N">
            </set>
            <set name="Victory Smite-DEX-N" baseset="Victory Smite-ACC-N">
            </set>
            <set name="Victory Smite-DEX-Berserk" baseset="Victory Smite-DEX-N">
            </set>
            <set name="Victory Smite-ATT-N" baseset="Victory Smite-ACC-N">
                                <ammo>Thew Bomblet</ammo>
            </set>
            <set name="Victory Smite-ATT-Berserk" baseset="Victory Smite-ATT-N">
            </set>
            <set name="Ascetic's Fury">
                                <ammo>Thew Bomblet</ammo>
                                <head>Aias Bonnet</head>
                                <neck>Rancor Collar</neck>
                                <lear>Brutal Earring</lear>
                                <rear>Kemas Earring</rear>
                                <body>Tantra Cyclas +2</body>
                                <hands>Heafoc Mitts</hands>
                                <lring>Epona's Ring</lring>
                                <rring>Spiral Ring</rring>
                                <back>Atheling Mantle</back>
                                <waist>Pipilaka Belt</waist>
                                <legs>Tantra Hose +2</legs>
                                <feet>Tantra Gaiters +2</feet>
            </set>
            <set name="Asuran Fists">
                                <ammo>Tiphia sting</ammo>
                                <head>Genbu's Kabuto</head>
                                <neck>Peacock amulet</neck>
                                <rear>Merman's earring</rear>
                                <lear>Merman's earring</lear>
                                <body>Scp. Harness +1</body>
                                <hands>Bandomusha kote</hands>
                                <lring>Toreador's ring</lring>
                                <rring>Soil Ring</rring>
                                <back>Amemet mantle +1</back>
                                <waist>Warwolf belt</waist>
                                <legs>Republic subligar</legs>
                                <feet>Seihanshi Habaki</feet>
            </set>
            <set name="Dragon Kick">
                                <head>Empress Hairpin</head>
                                <neck>Spike Necklace</neck>
                                <lear>Merman's earring</lear>
                                <rear>Brutal Earring</rear>
                                <body>Scp. Harness +1</body>
                                <hands>Alkyoneus's Brc.</hands>
                                <lring>Flame Ring</lring>
                                <rring>Flame Ring</rring>
                                <back>Cerberus Mantle</back>
                                <waist>Warwolf belt</waist>
                                <legs>Garrison Hose</legs>
                                <feet>Seihanshi Habaki</feet>
            </set>
            <set name="Tornado Kick">
                                <head>Aias Bonnet</head>
                                <neck>Rancor Collar</neck>
                                <lear>Brutal Earring</lear>
                                <rear>Kemas Earring</rear>
                                <body>Tantra Cyclas +2</body>
                                <hands>Heafoc Mitts</hands>
                                <lring>Spiral Ring</lring>
                                <rring>Rajas Ring</rring>
                                <back>Atheling Mantle</back>
                                <waist>Black Belt</waist>
                                <!--<legs>Shura Haidate</legs>-->
                                <feet>Tantra Gaiters +2</feet>
            </set>
            <set name="Retribution">
                                <ammo>Thew Bomblet</ammo>
                                <head>Aias Bonnet</head>
                                <neck>Rancor Collar</neck>
                                <lear>Brutal Earring</lear>
                                <rear>Kemas Earring</rear>
                                <body>Tantra Cyclas +2</body>
                                <hands>Heafoc Mitts</hands>
                                <lring>Spiral Ring</lring>
                                <rring>Rajas Ring</rring>
                                <back>Atheling Mantle</back>
                                <waist>Shadow Belt</waist>
                                <!--<legs>Shura Haidate</legs>-->
                                <feet>Tantra Gaiters +2</feet>
            </set>
            <set name="Full Swing">
                                <head>Aias Bonnet</head>
                                <neck>Rancor Collar</neck>
                                <lear>Brutal Earring</lear>
                                <rear>Kemas Earring</rear>
                                <body>Tantra Cyclas +2</body>
                                <hands>Heafoc Mitts</hands>
                                <lring>Spiral Ring</lring>
                                <rring>Rajas Ring</rring>
                                <back>Atheling Mantle</back>
                                <waist>Anguinus Belt</waist>
                                <!--<legs>Shura Haidate</legs>-->
                                <feet>Tantra Gaiters +2</feet>
            </set>
            <set name="Cataclysm">
                                <ammo>Tantra Tathlum</ammo>
                                <head>Aias Bonnet</head>
                                <neck>Artemis' Medal</neck>
                                <lear>Moldavite Earring</lear>
                                <rear>Hecate's Earring</rear>
                                <body>Tantra Cyclas +2</body>
                                <hands>Heafoc Mitts</hands>
                                <lring>Spiral Ring</lring>
                                <rring>Rajas Ring</rring>
                                <back>Vigilance Mantle +1</back>
                                <waist>Warwolf Belt</waist>
                                <!--<legs>Denali Kecks</legs>-->
                                <feet>Tantra Gaiters +2</feet> 
            </set>
            <set name="WS Base">
                                <head></head>
                                <neck></neck>
                                <lear></lear>
                                <rear></rear>
                                <body></body>
                                <hands></hands>
                                <lring></lring>
                                <rring></rring>
                                <back></back>
                                <waist></waist>
                                <legs></legs>
                                <feet></feet>
            </set>
            <set name="HundredFistsSet">
                                <ammo>Tiphia Sting</ammo>
                                <head>Empress hairpin</head>
                                <neck>Peacock amulet</neck>
                                <lear></lear>
                                <rear>Brutal Earring</rear>
                                <body>Scp. Harness +1</body>
                                <hands>Bandomusha Kote</hands>
                                <lring>Toreador's ring</lring>
                                <rring>Sniper's ring +1</rring>
                                <back>Amemet mantle +1</back>
                                <waist>Warwolf belt</waist>
                                <legs>Republic subligar</legs>
                                <feet>Seihanshi Habaki</feet>
            </set>
            <set name="Boost">
                <hands>Temple Gloves</hands>
            </set>
            <set name="Focus">
                <head>Temple Crown</head>
            </set>
            <set name="Dodge">
                <feet>Temple Gaiters</feet>
            </set>
            <set name="Chi Blast">
                                <ammo>Tantra Tathlum</ammo>
                                <head>Temple Crown</head>
                                <body>Temple Cyclas</body>
                                <back></back>
                                <feet>Suzaku's Sune-ate</feet>
								<rring>Soil Ring</rring>
								<lring>Soil Ring</lring>
            </set>
            <set name="Chakra">
                                <ammo>Bibiki seashell</ammo>
                                <head>Genbu's Kabuto</head>
                                <body>Temple Cyclas</body>
                                <hands>Melee Gloves</hands>
                                <rring>soil ring</rring>
                                <back>Melee Cape</back>
                                <waist>Warwolf Belt</waist>
								<lring>Soil Ring</lring>
								<legs>Republic subligar</legs>
            </set>
            <set name="Footwork">
			<feet>Seihanshi habaki</feet>
            </set>
            <set name="Counterstance">
                                <feet>Melee Gaiters</feet>
            </set>
            <set name="ImpetusSet">
                                <body>Tantra Cyclas +2</body>
            </set>
            <set name="PerfectCounterSet">
            </set>
            <set name="Utsusemi-Precast">
                                <lear>Loquac. Earring</lear>
                <neck>Magoraga Beads</neck>
            </set>
            <set name="Utsusemi-Midcast-PDT" baseset="PDT">
            </set>
            <set name="Utsusemi-Midcast-Counter" baseset="Utsusemi-Midcast-PDT">
                                <back>Boxer's mantle</back>
								<body>Scp. Harness +1</body>
            </set>
            <set name="Utsusemi-Midcast-EVA" baseset="FullEvasion">
            </set>
            <set name="Ninjutsu-Nukes">
                <main>$Staff-%SpellElement</main>
            </set>
            <set name="Haste">
                                <head>Walahra turban</head>
                                <neck></neck>
                                <hands></hands>
                                <waist>Brown Belt</waist>
                                <legs></legs>
								<feet>Sarutobi Kyahan</feet>
            </set>
        </group>
        <group name="Abyssea-NM" inherit="Abyssea-R" />
        <group name="Outside-R" inherit="Abyssea-R" default="true"/>
        <group name="Outside-NM" inherit="Outside-R" />
    </sets>
    <rules>
        <!--- Core Include Rules --->
        <xi:include href="Akyrey_Includes.xml" xpointer="//include[@name='LVrestriction']/*" />
        <xi:include href="Akyrey_Includes.xml" xpointer="//include[@name='ReturnRules']/*" />
        <xi:include href="Akyrey_Includes.xml" xpointer="//include[@name='CleanTransportation']/*" />
        <xi:include href="Akyrey_Includes.xml" xpointer="//include[@name='AreaRule']/*" />
        <xi:include href="Akyrey_Includes.xml" xpointer="//include[@name='LockWeaponRule']/*" />
        <xi:include href="Akyrey_Includes.xml" xpointer="//include[@name='SpellCancel']/*" />
        <xi:include href="Akyrey_Includes.xml" xpointer="//include[@name='AttackEarring']/*" />
        <!--- Optional Include Rules --->
        <!--- Automatically change variables when buffs wear off --->
        <if notBuffactive="Hundred Fists" advanced='"$HundredFistsSet"!="BlankSet"'>
            <var cmd="set HundredFistsSet BlankSet" />
        </if>
        <if notBuffactive="Perfect Counter" advanced='"$PerfectCounterSet"!="BlankSet"'>
            <var cmd="set PerfectCounterSet BlankSet" />
        </if>
                <if notBuffactive="Impetus" advanced='"$ImpetusSet"!="BlankSet"'>
            <var cmd="set ImpetusSet BlankSet" />
        </if>
                <if notBuffactive="Footwork" advanced='"$STYLE"!="H2H"'>
            <var cmd="set STYLE H2H" />
        </if>
                <if notBuffactive="Berserk" advanced='"$Berserk"!="N"'>
            <var cmd="set Berserk N" />
        </if>
        <!--- Automatically Equip Gear Rules --->
        <command when="engaged|idle|aftercast|resting">Dancing Chains</command>
        <!--- Automatically change group --->
        <if notgroup="$Area-$Resist">
            <command>sc group $Area-$Resist</command>
        </if>
        <!--- Trigger Spells --->
        <if spell="$TriggerSetOne|$TriggerSetTwo|$TriggerSetThree">
            <if spell="$TriggerSetOne">
                <!--- Auto Update Gear --->
                <if spell="Dancing Chains">
                    <cancelspell />
                    <if status="idle">
                        <equip set="%Status|$Armor-%Status|$Movement-%Status" />
                    </if>
                    <elseif status="engaged">
                        <if advanced='"$VAR-TP"="EVA"'>
                            <equip set="TP-$STYLE-$VAR-TP|$PerfectCounterSet|$Armor-%Status|$Movement-%Status" />
                        </if>
                        <else>
                            <equip set="TP-$STYLE-$VAR-TP|$HundredFistsSet|$ImpetusSet|$PerfectCounterSet|$Armor-%Status|$Movement-%Status" />
                        </else>
                    </elseif>
                    <elseif status="resting">
                        <equip set="%Status" />
                    </elseif>
                </if>
                <!--- Change the distance at which to cancel WS --->
                <xi:include href="Akyrey_Includes.xml" xpointer="//include[@name='SetDistanceVariable']/*" />
                <!--- Change the resistance variable: Regular mobs or NMs --->
                <xi:include href="Akyrey_Includes.xml" xpointer="//include[@name='ResistRule']/*" />
                <!--- Change the Armor variable: Blank, MDT, PDT, or Full Evasion --->
                <xi:include href="Akyrey_Includes.xml" xpointer="//include[@name='Variable-Blank']/*" />
                <xi:include href="Akyrey_Includes.xml" xpointer="//include[@name='Variable-MDT']/*" />
                <xi:include href="Akyrey_Includes.xml" xpointer="//include[@name='Variable-PDT']/*" />
                <xi:include href="Akyrey_Includes.xml" xpointer="//include[@name='Variable-FullEvasion']/*" />
            </if>
            <elseif spell="$TriggerSetTwo">
                <!--- Change TP set type --->
                <if spell="Poison V">
                    <cancelspell />
                    <if advanced='"$VAR-TP"="HASTE"'>
                        <var cmd="set VAR-TP ACC" />
                    </if>
                    <elseif advanced='"$VAR-TP"="ACC"'>
                        <var cmd="set VAR-TP PDT" />
                    </elseif>
                    <elseif advanced='"$VAR-TP"="PDT"'>
                        <var cmd="set VAR-TP EVA" />
                    </elseif>
                    <elseif advanced='"$VAR-TP"="EVA"'>
                        <var cmd="set VAR-TP DEX" />
                    </elseif>
                    <elseif advanced='"$VAR-TP"="DEX"'>
                        <var cmd="set VAR-TP HASTE" />
                    </elseif>
                    <addtochat color="135">TP Variable: $VAR-TP</addtochat>
                    <if status="engaged">
                        <command>Dancing Chains</command>
                    </if>
                </if>
                <!--- Change WS set type --->
                <elseif spell="Poisonga V">
                    <cancelspell />
                    <if advanced='"$VAR-WS"="ATT"'>
                        <var cmd="set VAR-WS ACC" />
                    </if>
                    <elseif advanced='"$VAR-WS"="ACC"'>
                        <var cmd="set VAR-WS DEX" />
                    </elseif>
                    <elseif advanced='"$VAR-WS"="DEX"'>
                        <var cmd="set VAR-WS ATT" />
                    </elseif>
                    <addtochat color="135">WS Variable: $VAR-WS2</addtochat>
                </elseif>
                <!--- Change Midcast for Utsusemi --->
                <elseif spell="Scop's Operetta">
                    <cancelspell />
                    <if advanced='"$VAR-Utsusemi"="PDT"'>
                        <var cmd="set VAR-Utsusemi Counter" />
                    </if>
                    <elseif advanced='"$VAR-Utsusemi"="Counter"'>
                        <var cmd="set VAR-Utsusemi EVA" />
                    </elseif>
                    <elseif advanced='"$VAR-Utsusemi"="EVA"'>
                        <var cmd="set VAR-Utsusemi PDT" />
                    </elseif>
                    <addtochat color="135">Utsusemi Midcast: $Var-Utsusemi</addtochat>
                </elseif>
                <!--- Change specific pieces of gear (Self customize this one if you want) --->
                <elseif spell="Shining Fantasia">
                    <cancelspell />
                    <if advanced='"$EquipmentSlot-Set"="EX1"'>
                        <var cmd="set EquipmentSlot-Set EX2" />
                    </if>
                    <elseif advanced='"$Main-Idle"="EX2"'>
                        <var cmd="set EquipmentSlot-Set EX1" />
                    </elseif>
                    <command>Dancing Chains</command>
                </elseif>
                <!--- Add or Remove Movement gear --->
                <elseif spell="Raptor Mazurka">
                    <cancelspell />
                    <if advanced='"$Movement-%Status"="BlankSet"'>
                        <var cmd="set Movement-%Status Movement" />
                        <addtochat color="135">Movement Speed: ON</addtochat>
                    </if>
                    <else>
                        <var cmd="set Movement-%Status BlankSet" />
                        <addtochat color="135">Movement Speed: OFF</addtochat>
                    </else>
                    <command>Dancing Chains</command>
                </elseif>
            </elseif>
            <else>
                <!--- Class Specific Trigger 1 --->
                <if spell="Foxfire">
                    <cancelspell />
                </if>
                <!--- Class Specific Trigger 2 --->
                <elseif spell="Netherspikes">
                    <cancelspell />
                </elseif>
                <!--- Class Specific Trigger 3 --->
                <elseif spell="Diaga V">
                    <cancelspell />
                </elseif>
                <!--- Class Specific Trigger 4 --->
                <elseif spell="Banishga V">
                    <cancelspell />
                </elseif>
                <!--- Class Specific Trigger 5 --->
                <elseif spell="Goblin Gavotte">
                    <cancelspell />
                </elseif>
            </else>
        </if>
        <elseif type="Ninjutsu">
            <!--- Ninjutsu: Utsusemi --->
            <if spell="Utsusemi: Ichi">
                <equip when="precast" set="Utsusemi-Precast" />
                <command when="precast">wait 0.5; sc set "Utsusemi-Midcast-$VAR-Utsusemi"</command>
                <midcastdelay delay="2" />
                <equip when="midcast" set="Haste" />
            </if>
            <elseif spell="Utsusemi: Ni">
                <equip when="precast|midcast" set="Haste" />
            </elseif>
            <elseif spell="Katon*|Doton*|Suiton*|Huton*|Hyoton*|Raiton*">
                <equip when="midcast" set="Ninjutsu-Nukes" />
            </elseif>
        </elseif>
                <elseif CommandPrefix="/range" notEquipRange="$R-Weapon">
                        <castdelay delay="$Delay-JA" />
                        <equip when="precast">
                        </equip>
                </elseif>
        <elseif type="WeaponSkill">
            <castdelay delay="$Delay-JA" />
            <if spell="Victory Smite">
                <equip set="%Spell-$VAR-WS-$Berserk|$ImpetusSet" />
            </if>
            <elseif Spell="Ascetic's Fury|Asuran Fists|Dragon Kick|Tornado Kick|Retribution|Full Swing|Cataclysm">
                <equip set="%Spell|$ImpetusSet" />
            </elseif>
            <else>
                <equip set="WS Base" />
            </else>
                        <action type="Command" when="aftercast">input /echo %spell TP return: &lt;tp&gt;</action>
        </elseif>
        <elseif type="JobAbility">
            <!--- Precast-only JAs --->
            <if spell="Boost|Focus|Dodge|Chakra|Chi Blast|Counterstance">
                <castdelay delay="$Delay-JA" />
                <equip when="precast" set="%Spell" />
            </if>
            <!--- Variable Changing and Precast gear JAs --->
            <elseif Spell="Impetus">
                <var cmd="set ImpetusSet ImpetusSet" />
            </elseif>
            <elseif Spell="Perfect Counter">
                <var cmd="set PerfectCounterSet PerfectCounterSet" />
            </elseif>
            <elseif Spell="Berserk">
                <var cmd="set Berserk Berserk" />
            </elseif>
            <elseif Spell="Footwork">
                <var cmd="set STYLE KICK" />
            </elseif>
            <elseif Spell="Hundred Fists">
                <var cmd="set HundredFistsSet HundredFistsSet" />
            </elseif>
        </elseif>
        <elseif type="Samba|Waltz|Flourish*|Jig">
            <return />
        </elseif>
    </rules>
</spellcast>
