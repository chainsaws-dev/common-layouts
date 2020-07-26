# Main things to remember

## Super centered

`display: grid;`
`place-items: center;`

## Deconstructed pancake

That growth width
`flex: 1 1 150px;`

That reaches 150 px
`flex: 0 1 150px;`

## Sidebar says

`grid-template-columns: minmax(150px, 25%) 1fr;`

## Pancake stack

`grid-template-rows: auto 1fr auto;`

## Holy grail

in parent:

`grid-template: auto 1fr auto / auto 1fr auto;`

in each child:

`display: block; grid-column: 1 / 4;`

means draw this from begining of first grid column to the begining of fourth (end of third)

## Span grid (Brick wall)

in parent:

`grid-template-columns: repeat(12, 1fr);`

==

`grid-template-columns: 1fr 1fr 1fr ... (12 times)`

in each child:

`grid-column: 1 / span 12;`

## RAM (Repeat Auto Minmax)

`display: grid;`
`grid-gap: 1rem;`
`grid-template-columns: repeat(auto-fit, minmax(150px, 1fr));`
