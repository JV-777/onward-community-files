# Onward: способности, на которые влияет Silence


## Правило эффекта

> Prevent the ability on the hero's sheet, on all friendly spell cards attached to them. Also prevent any temporary, delayed, or triggered effects granted by friendly spells.

Errata:

- Temporary: «until end of this turn/round…», «this turn/round…».
- Triggered: «when…».
- Delayed: «At the end of the round…», «immediately after this round…».



**[B1] [Silence, clarification](https://boardgamegeek.com/thread/3598967/silence-clarification).** Участник Mark Buxton объясняет различие между разрешением заклинания и предоставленными им длительными эффектами ([ответ от 26.10.2025](https://boardgamegeek.com/thread/3598967/article/46791174)). Для Siege Masters он прямо связывает результат с наличием Silence на Doomies в момент отложенного push, а не в момент розыгрыша ([ответ от 27.10.2025](https://boardgamegeek.com/thread/3598967/article/46798007)). В последующем ответе он отделяет мгновенное разрешение от эффекта, происходящего позже ([14.11.2025](https://boardgamegeek.com/thread/3598967/article/46887639)). Эти ответы использованы как разъяснение сообщества; статус официального решения автора игры им не приписывается.

**[B2] [Silence on a reactive card and the stack](https://boardgamegeek.com/thread/3595496/article/46760949).** Ответ уточняет, что Silence не запрещает само произнесение и разрешение заклинаний: мгновенное перемещение и временное повышение брони обрабатываются по-разному.

**Перенос фазы миньонов — нет ответа.** 
На момент отчета явного ответа после него нет. Поэтому для Bloodthirst, Biding Time и Living Jungle уверенно отмечены только бонусы характеристик. Будет уточнено позднее.

## Способности, на которые влияет Silence

### Akimo

#### Kurumo's Brand — `twoTwoCard`

> Deal 3 DMG and BURN 1 ::target:: nearby enemy hero or outsider.
> The next time that enemy enters an area this turn, teleport Akimo there.

**Вывод:** Триггер следующего входа врага в область предоставляет Akimo отложенный телепорт. Silence на Akimo подавляет этот телепорт; первоначальные 3 DMG и BURN остаются мгновенными.

#### Ishiro Unleashed — `threeOneCard`

> ~Additional cost: 1 HP.
> Akimo's next attack this turn has +5 strength and also deals BURN.

**Вывод:** Silence на Akimo подавляет усиление следующей атаки в этот ход: +5 strength и дополнительный BURN. Это временный эффект, а не атака при разрешении карты.

#### Bloodthirst — `fourOneCard`

> ~Cast only during your shop phase.
> Akimo has +3 initiative and +1 strength this round.
> The next minion phase is delayed until the end of this round.

**Вывод:** Silence на Akimo подавляет +3 initiative и +1 strength на раунд. Влияние на перенос фазы миньонов — нет ответа; см. оговорку ниже.

### Shyllavi

#### Wildcat Form — `twoTwoCard`

> ~Attach to Shyllavi until she is defeated.
> She has +1 armor and "Retaliate: DISARM".

**Вывод:** Дружественная карта прикреплена к Shyllavi: Silence на ней подавляет +1 armor и Retaliate: DISARM.

#### Biding Time — `threeOneCard`

> ~Cast only during your shop phase.
> Heal 3 HP to Shyllavi.
> She has +3 initiative this round.
> The next minion phase is delayed until the end of this round.

**Вывод:** Silence на Shyllavi подавляет +3 initiative на раунд, но не мгновенное лечение 3 HP. Влияние на перенос фазы миньонов — нет ответа; см. оговорку ниже.

#### Feline Pounce — `fourOneCard`

> Teleport to 1 ::target:: area exactly 2 areas away.
> If you do, SILENCE 1 hero there and prevent their next cast action this turn.

**Вывод:** Условно: карта допускает выбор союзного героя, поскольку написано «1 hero», а не «enemy hero». Для такого получателя запрет следующего cast action в этот ход является временным эффектом дружественного заклинания и подавляется его Silence (сама карта накладывает SILENCE). На вражеском получателе этот довод не работает. Телепорт и наложение статуса не являются отложенными эффектами.

### Nantaca

#### Living Jungle — `fourOneCard`

> ~Cast only during your shop phase and only if Nantaca is in a jungle.
> Teleport to 1 ::target:: jungle area anywhere without enemy heroes.
> She has +2 initiative this round.
> The next minion phase is delayed until the end of this round.

**Вывод:** Silence на Nantaca подавляет +2 initiative на раунд; первоначальный телепорт остаётся мгновенным. Влияние на перенос фазы миньонов — нет ответа; см. оговорку ниже.

### Haburat

#### Overdue Execution — `threeOneCard`

> ~Cast only during your shop phase.
> Haburat has +X initiative and +X strength this round, where X is the Day number.
> Choose 1 enemy hero anywhere, Haburat can only attack them this round.

**Вывод:** Silence на Haburat подавляет временные +X initiative, +X strength и ограничение атак выбранным героем на раунд. Дружественное происхождение эффекта не означает, что подавляются только выгодные части.

#### Weave — `fourOneCard`

> Choose 1 ::target:: nearby enemy.
> Haburat's next attack this turn ignores the "Weak Enemies" rule and deals any excess DMG to the chosen enemy.
> Excess DMG is any DMG beyond what is needed to defeat the target.

**Вывод:** Модификация следующей атаки Haburat в этот ход — временный эффект: игнорирование Weak Enemies и перенос избыточного урона подавляются Silence на Haburat.

#### Lightning Blades — `ultimate`

> ~Cast only during your shop phase.
> Double the AP on Haburat's plan card this round.

**Вывод:** Удвоение AP на plan card действует «this round»: считаю это временным модификатором Haburat, подавляемым Silence на нём, а не мгновенной выдачей AP.

### Sakoshi

#### Shuriken Storm — `ultimate`

> ~Cast only during your shop phase.
> Sakoshi gains 3 AP.
> This round, he can take attack actions, but may only target heroes and/or outsiders.

**Вывод:** Silence на Sakoshi подавляет предоставленное на раунд разрешение на attack actions вместе с ограничением целей. Мгновенно полученные 3 AP не отменяются задним числом.

### Vorhild

#### Ermine Form — `twoTwoCard`

> ~Attach to Vorhild until she declares an attack or cast action.
> She has Tough during any hero's turn.

**Вывод:** Дружественная карта прикреплена к Vorhild. Silence на ней подавляет предоставленную Tough; условие длительности прикрепления не делает эффект мгновенным.

### Khepiax

#### Chain Lightning — `twoTwoCard`

> ~Additional cost: discard 1 card from hand.
> Khepiax's next attack this turn may target up to 3 additional enemies in her area.

**Вывод:** Дополнительные цели следующей атаки в этот ход — временный эффект Khepiax, подавляемый Silence на ней.

### Setheru

#### Word of Command — `fourOneCard`

> ~Channel only during your shop phase.
> For every 2 charges on this, choose one, same or different effect:
> - Draw 1 card.
> - Displace 1 ::target:: nearby hero.
> - Setheru has +1 momentum this round.

**Вывод:** Только вариант «Setheru has +1 momentum this round» является временным эффектом и подавляется Silence на Setheru. Добор карты и displace разрешаются сразу; само условие Channel during shop phase не является основанием для отметки.

### Doomies

#### Siege Masters — `twoTwoCard`

> ~Cast only during your shop phase.
> Immediately after this round, push with the friendly minions in Doomies' area.

**Вывод:** Push после раунда — отложенный эффект, связанный с Doomies. Он подавляется, если на Doomies есть Silence в момент срабатывания. Этот случай прямо разобран участниками BGG [B1].

#### Join Us — `threeOneCard`

> ~Attach to Doomies until they are defeated.
> When a nearby enemy minion is defeated, heal 2 HP to Doomies.

**Вывод:** Дружественная карта прикреплена к Doomies и даёт триггер лечения при гибели ближайшего вражеского миньона. Silence на Doomies подавляет этот триггер.

#### BOOM!!! — `ultimate`

> ~Cast only during your shop phase.
> Immediately after this round, deal 4 DMG to 1 enemy nexus or tower within 3 areas ignoring its Tough and Retaliate abilities.

**Вывод:** Урон сразу после раунда — отложенный эффект Doomies: Silence на них в момент срабатывания подавляет его. Это применение того же принципа, который разобран для Siege Masters [B1].

### Astryda

#### Freeze Push — `twoTwoCard`

> ~Cast only during your shop phase and attach to Astryda until the end of this round.
> Prevent the push of all nearby minions.

**Вывод:** Дружественная карта прикреплена к Astryda. Silence на Astryda подавляет её запрет push ближайших миньонов, хотя сами миньоны не являются носителями карты.

### Kohai

#### Grit and Grin — `threeOneCard`

> Heal 4 HP to Kohai.
> This turn, he has +1 armor and when an opponent chooses a target for an attack they must target Kohai, if possible.

**Вывод:** Silence на Kohai подавляет +1 armor на ход и временный триггер обязательного выбора Kohai целью атаки. Лечение 4 HP выполняется сразу.

### Ekhrit

#### Stasis Push — `twoTwoCard`

> ~Cast only during your shop phase and attach to Ekhrit until the end of this round.
> This round, prevent the push of minions NOT nearby to Ekhrit.

**Вывод:** Дружественная карта прикреплена к Ekhrit. Silence на Ekhrit подавляет запрет push миньонов, находящихся не рядом с ней.

#### Windborne — `threeOneCard`

> Move 1 ::target:: other friendly hero within 2 areas up to 2 times.
> They get +1 momentum this round.

**Вывод:** Silence на дружественном герое-получателе подавляет +1 momentum на раунд. Два перемещения выполняются сразу; Silence только на Ekhrit не считаю достаточным основанием отключить бонус другого героя.

### Kumaya

#### Shroud Smite — `zeroThreeCard`

> Kumaya has +2 armor this turn.
> Then, attack with +2 strength up to 1 ::target:: outsider or monster in her area.

**Вывод:** Silence на Kumaya подавляет +2 armor на ход. Последующая атака с +2 strength непосредственно в разрешении карты сама по себе не является временным или отложенным эффектом.

#### Smokescreen — `twoTwoCard`

> ~Attach to Kumaya until she is defeated.
> Enemies outside of Kumaya's area cannot target units in her area or the area itself.

**Вывод:** Дружественная карта прикреплена к Kumaya: Silence на ней подавляет ограничение выбора целей врагами вне её области.

#### Explosive Resolve — `threeOneCard`

> Kumaya has +2 armor this turn.
> Deal 2 DMG and BURN up to 2 ::target:: enemy heroes in her area.

**Вывод:** Silence на Kumaya подавляет +2 armor на ход. Урон и BURN разрешаются сразу.

### Heraal

#### Ironwood Smite — `zeroThreeCard`

> Heraal has +2 armor this turn.
> Deal 3 DMG to up to 1 ::target:: nearby monster or outsider.

**Вывод:** Silence на Heraal подавляет +2 armor на ход; 3 DMG монстру или outsider — мгновенная часть.

#### Elk Form — `twoTwoCard`

> ~Attach to Heraal until he is defeated.
> When Heraal enters an area, he may deal 2 DMG to 1 ::target:: monster or outsider there. (Once per Heraal's turn.)

**Вывод:** Дружественное прикрепление даёт Heraal триггер урона при входе в область. Silence на Heraal подавляет его.

#### The Wilds Ride — `ultimate`

> ~Cast only during your shop phase.
> Immediately after Heraal passes this round, deal X DMG to 1 enemy in Heraal's area, where X are the MP he spent this turn. This DMG ignores the Tough ability.

**Вывод:** Урон после pass Heraal в этом раунде происходит позже разрешения карты. Это отложенный эффект, подавляемый Silence на Heraal в момент срабатывания.

### Ixatosk

#### Split Form — `twoTwoCard`

> ~Attach to Ixatosk until he is defeated.
> When the jungling phase ends, you may deal 1 DMG to 1 ::target:: monster or outsider within 2 areas.

**Вывод:** Дружественное прикрепление даёт триггер после завершения jungling phase. Silence на Ixatosk подавляет предоставленный картой урон.

#### Counterstrike — `threeOneCard`

> Ixatosk has +2 armor this turn.
> Deal 2 DMG to up to 1 ::target:: enemy hero in Ixatosk's area.

**Вывод:** Silence на Ixatosk подавляет +2 armor на ход. Урон разрешается сразу.

#### Tunnel Gank — `fourOneCard`

> Teleport 1 ::target:: nearby friendly hero to 1 ::target:: jungle area without enemy heroes.
> That hero has +1 strength this turn.

**Вывод:** Silence на дружественном герое-получателе подавляет +1 strength на ход. Телепорт выполняется сразу.

#### Skytear Predator — `ultimate`

> ~Cast only during your shop phase.
> Ixatosk has +X strength and +X armor this round, where X are the MP on its plan.
> Ixatosk's attacks can only target the outsider this round, ignoring its Tough ability.

**Вывод:** Silence на Ixatosk подавляет временные +X strength и +X armor, а также правило атак на этот раунд: только outsider с игнорированием Tough.

### Shafathi

#### Shafathi Shadow — `twoTwoCard`

> ~Attach to Shafathi until he is defeated.
> When he defeats a monster, earn 3 gold.

**Вывод:** Дружественная карта прикреплена к Shafathi и даёт триггер получения золота при победе над монстром. Silence на Shafathi подавляет триггер; уже полученное золото не отнимается.

#### Dematerialize — `threeOneCard`

> Shafathi has Tough this turn.
> Deal 1 piercing DMG and SILENCE up to 1 ::target:: enemy hero in his area.

**Вывод:** Silence на Shafathi подавляет Tough на ход. Piercing DMG и SILENCE по врагу разрешаются сразу.

### Yami

#### Ghost Walk — `threeOneCard`

> Yami gains 2 MP.
> This turn, she can take move actions, and she has Tough.

**Вывод:** Silence на Yami подавляет Tough и предоставленное на ход разрешение брать move actions. Мгновенная выдача 2 MP не отменяется задним числом.

### Gulbjarn

#### Fearless Lead — `zeroThreeCard`

> ~Attach to Gulbjarn until the end of this round.
> Gulbjarn has +2 momentum.

**Вывод:** Дружественное прикрепление до конца раунда: Silence на Gulbjarn подавляет +2 momentum.

#### Bear Form — `twoTwoCard`

> ~Attach to Gulbjarn until he is defeated.
> Gulbjarn has +1 armor.
> Prevent the "move", "teleport", and "displace" effects of spells and abilities of ::target:: nearby enemy heroes.

**Вывод:** Дружественное прикрепление: Silence на Gulbjarn подавляет +1 armor и исходящий от карты запрет move/teleport/displace во вражеских заклинаниях и способностях.

#### Iron Grasp — `threeOneCard`

> Deal 3 DMG, DISARM, and pull 1 ::target:: nearby enemy hero.
> Neither Gulbjarn nor the target can declare cast actions this turn.

**Вывод:** Запрет самому Gulbjarn объявлять cast actions в этот ход — временный эффект его дружественного заклинания, поэтому считаю его подавляемым Silence на Gulbjarn. Запрет для вражеской цели от этого автоматически не снимается. Урон, DISARM и pull мгновенные.

### Zacoal

#### Towering Lead — `zeroThreeCard`

> ~Attach to Zacoal until the end of this turn.
> Nearby friendly minions have +3 armor.

**Вывод:** Дружественная карта прикреплена к Zacoal: Silence на Zacoal подавляет исходящий от неё бонус +3 armor ближайшим дружественным миньонам.

#### \*Whheeeeee\* — `twoTwoCard`

> FREEZE and teleport 1 nearby hero to an area adjacent to them.
> They cannot declare cast actions this turn.

**Вывод:** Условно: можно выбрать дружественного героя («1 nearby hero»). Его Silence подавляет запрет объявлять cast actions на ход, полученный от дружественного заклинания. FREEZE и телепорт — мгновенные; для вражеской цели основание friendly spells не выполнено.

#### \*Thud\* \*Thud\* — `threeOneCard`

> This turn, when Zacoal teleports a unit to an area, he may deal 1 DMG and DISARM up to 2 ::target:: enemies there.

**Вывод:** Silence на Zacoal подавляет предоставленный на ход триггер урона и DISARM после телепортации юнита.

#### \*Clonk\* — `fourOneCard`

> Zacoal has +2 armor this turn.
> Deal 3 DMG to up to 1 ::target:: nearby enemy hero.

**Вывод:** Silence на Zacoal подавляет +2 armor на ход. 3 DMG разрешаются сразу.

### Khenui

#### Deceptive Lead — `zeroThreeCard`

> ~Attach to Khenui until the end of this round.
> Prevent the Retaliate ability of nearby enemies.

**Вывод:** Дружественное прикрепление: Silence на Khenui подавляет исходящий от карты запрет Retaliate ближайших врагов.

#### Elusive Spin — `threeOneCard`

> Khenui has +3 armor this turn.
> SILENCE or STUN up to 1 ::target:: nearby enemy hero.

**Вывод:** Silence на Khenui подавляет +3 armor на ход. Наложение SILENCE или STUN на врага происходит сразу.

#### Magnetic Presence — `fourOneCard`

> ~Cast only during your shop phase.
> ~Attach to Khenui until the end of the round.
> Enemy heroes within 3 areas cannot attack unless they are nearby to Khenui or have 0 MP left.
> If those heroes declare a move action, they must move closer to her. (Does not apply to movement from spells such as Flash.)

**Вывод:** Дружественная карта прикреплена к Khenui: Silence на ней подавляет оба исходящих ограничения — на атаки врагов и направление их move actions.

#### Echo Dance — `ultimate`

> ~Cast only during your shop phase.
> Khenui has +2 initiative this round and may teleport to 1 ::target:: other area anywhere.
> If you do, deal 2 DMG and DISARM 1 enemy hero there.

**Вывод:** Silence на Khenui подавляет +2 initiative на раунд. Телепорт и последующие DMG/DISARM входят в непосредственное разрешение карты.

### Hogosai

#### Brimstone Shield — `zeroThreeCard`

> 1 ::target:: nearby unit has +3 armor and "Retaliate: BURN" this turn.

**Вывод:** Если получатель — дружественный герой, Silence на нём подавляет +3 armor и Retaliate: BURN на ход. Отметка не означает, что Silence на Hogosai отключает щит другого героя.

#### Infernal Taunt — `twoTwoCard`

> ~Attach to Hogosai until it is defeated.
> It has +1 armor and "Retaliate: BURN".
> When an opponent chooses a target for a spell or ability they must target Hogosai, if possible.

**Вывод:** Дружественное прикрепление: Silence на Hogosai подавляет +1 armor, Retaliate: BURN и требование выбирать Hogosai целью заклинания или способности.

### Brylvar

#### Frost Shield — `zeroThreeCard`

> 1 ::target:: nearby unit has +3 armor and "Retaliate: FREEZE" this turn.

**Вывод:** Если получатель — дружественный герой, Silence на нём подавляет временные +3 armor и Retaliate: FREEZE.

#### Pangolin Form — `twoTwoCard`

> ~Attach to Brylvar until he is defeated.
> He has +1 armor.
> If nearby heroes would take DMG, Brylvar may take any amount of it instead.
> (Both Brylvar and the friendly hero use their own armor.)

**Вывод:** Дружественная карта прикреплена к Brylvar: Silence на нём подавляет +1 armor и возможность принимать урон вместо ближайших героев.

#### Spiked Scales — `ultimate`

> This turn, 1 ::target:: nearby unit has +4 armor and "Retaliate: X DMG", where X is their armor.

**Вывод:** Если получатель — дружественный герой, Silence на нём подавляет +4 armor и Retaliate: X DMG на этот ход.

### Cotlic

#### Bone Shield — `zeroThreeCard`

> 1 ::target:: nearby unit has +3 armor and "Retaliate: DISARM" this turn.

**Вывод:** Если получатель — дружественный герой, Silence на нём подавляет +3 armor и Retaliate: DISARM на ход.

#### Flesh to Stone — `twoTwoCard`

> ~Attach to Cotlic until he is defeated.
> He has +2 armor and loses 1 AP each time he starts a turn.
> When an opponent chooses a target for an attack or cast action they must target Cotlic, if possible.

**Вывод:** Дружественное прикрепление: Silence на Cotlic подавляет +2 armor, потерю 1 AP при начале хода и требование выбирать его целью. Блокируется и отрицательная часть способности.

#### My Kingdom! — `ultimate`

> Immediately after this turn, push with the friendly minions in Cotlic's area with +2 momentum.

**Вывод:** Дополнительный push с +2 momentum сразу после этого хода — отложенный эффект Cotlic, подавляемый Silence на нём в момент срабатывания; аналогия с Siege Masters [B1].

### Shaidrus

#### Void Shield — `zeroThreeCard`

> 1 ::target:: nearby unit has +3 armor and "Retaliate: SILENCE" this turn.

**Вывод:** Если получатель — дружественный герой, Silence на нём подавляет +3 armor и Retaliate: SILENCE на ход.

#### Shaidrus Shadow — `twoTwoCard`

> ~Attach to 1 ::target:: friendly hero within 2 areas until Shaidrus is defeated.
> If the attached hero would take DMG, Shaidrus must take it instead.
> (Both Shaidrus and the attached hero use their own armor.)

**Вывод:** Дружественная карта прикреплена к выбранному герою: Silence на этом герое подавляет перенаправление его урона на Shaidrus. Из одного лишь Silence на Shaidrus не делаю вывода о подавлении карты, прикреплённой к другому герою.

### Miyuki

#### Lifesteal Touch — `threeOneCard`

> ~Attach to 1 ::target:: friendly hero within 3 areas until they are defeated.
> When the attached hero deals 1 or more DMG with an attack, heal 2 HP to them.

**Вывод:** Дружественная карта прикреплена к выбранному герою и даёт ему триггер лечения после нанесения урона атакой. Silence на получателе подавляет этот триггер.

#### Soul Guide — `ultimate`

> If 1 ::target:: outsider or friendly hero within 3 areas would be defeated this turn, set their HP to 5 instead.

**Вывод:** При выборе дружественного героя Silence на нём подавляет защиту от поражения в этот ход с установкой HP в 5. Это временный эффект замещения будущего события.

### Freyhel

#### Withering Gift — `threeOneCard`

> ~Attach to Freyhel until she is defeated.
> If she would heal a unit, she may deal the same amount of DMG instead.

**Вывод:** Дружественная карта прикреплена к Freyhel: Silence на ней подавляет возможность заменять лечение уроном.

### Tlakali

#### Ritual Heal — `zeroThreeCard`

> Heal 3 HP to 1 ::target:: nearby unit and remove 1 of their statuses.
> If Tlakali is in a contested area, the unit also has +1 armor this turn.

**Вывод:** Если Tlakali находится в contested area и получатель — дружественный герой, Silence на получателе подавляет +1 armor на ход. Лечение и снятие статуса выполняются сразу; если снят сам Silence, оценивать броню нужно уже после снятия.

### Akhuti

#### Radiant Healing — `zeroThreeCard`

> Heal 2 HP to up to 2 ::target:: nearby units and remove 1 of their statuses.
> Any of those units not at their starting HP level has +1 armor this turn.

**Вывод:** Silence на дружественном герое-получателе подавляет +1 armor на ход при выполнении условия по HP. Лечение и снятие статуса мгновенные; если снят Silence, он больше не мешает бонусу.

#### Silence Ray — `threeOneCard`

> FREEZE and BURN 1 hero within 2 areas.
> They cannot declare cast actions this turn.

**Вывод:** Условно: допустима дружественная цель («1 hero»). Её Silence подавляет запрет cast actions на ход как временный эффект дружественного заклинания, хотя эффект вредный. FREEZE и BURN разрешаются сразу; для врага этот довод не применим.

#### Peacekeeping Ray — `fourOneCard`

> You may remove 1 status from 1 ::target:: unit within 2 areas.
> Prevent the next time they would lose HP this turn.

**Вывод:** При выборе дружественного героя Silence на получателе подавляет защиту от следующей потери HP в этот ход. Снятие статуса — мгновенная часть; можно снять сам Silence до применения защиты.
