# Main things to remember

Samples taken from [here](http://1linelayouts.glitch.me/)
added some extra css and html to use as templates in practice

## Super centered
- [x] Edge
- [x] Firefox
- [x] Chrome
- [x] Safari

`display: grid;`

`place-items: center;`

## Deconstructed pancake
- [x] Edge
- [x] Firefox
- [x] Chrome
- [x] Safari

That growth width

`flex: 1 1 150px;`

That reaches 150 px

`flex: 0 1 150px;`

## Sidebar says
- [x] Edge
- [x] Firefox
- [x] Chrome
- [x] Safari

`grid-template-columns: minmax(150px, 25%) 1fr;`

## Pancake stack
- [x] Edge
- [x] Firefox
- [x] Chrome
- [x] Safari

`grid-template-rows: auto 1fr auto;`

## Holy grail
- [x] Edge
- [x] Firefox
- [x] Chrome
- [x] Safari

in parent:

`grid-template: auto 1fr auto / auto 1fr auto;`

in each child:

`display: block; grid-column: 1 / 4;`

means draw this from begining of first grid column to the begining of fourth (end of third)

## Span grid (Brick wall)
- [x] Edge
- [x] Firefox
- [x] Chrome
- [x] Safari

in parent:

`grid-template-columns: repeat(12, 1fr);`

==

`grid-template-columns: 1fr 1fr 1fr ... (12 times)`

in each child:

`grid-column: 1 / span 12;`

## RAM (Repeat Auto Minmax)
- [x] Edge
- [x] Firefox
- [x] Chrome
- [x] Safari

`display: grid;`

`grid-gap: 1rem;`

`grid-template-columns: repeat(auto-fit, minmax(150px, 1fr));`

`auto-fit` 

grows beyond 150px filling all free space

WHEN

`auto-fill`

doesn't grow beyond 150 px

## Line Up
- [x] Edge
- [x] Firefox
- [x] Chrome
- [ ] Safari

Parent

`grid-gap: 1rem;`

`grid-template-columns: repeat(3, 1fr);`

Item

`flex-direction: column;`

`justify-content: space-between;`

## Keep aspect ratio
- [ ] Edge
- [ ] Firefox
- [ ] Chrome
- [ ] Safari

Planned for future

`aspect-ratio: 16 / 9;`
