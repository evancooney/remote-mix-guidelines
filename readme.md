# Remote Mix Guidelines for Bandnada

This guides defines a consistent format and workflow for a remote mixer to transmit commands to the location mixer

## Command format

## [source](#source) :: [action](#actions) :: [amount](#amount) :: [frequency(optional)](#frequency)

### Examples

 Turn bass up by 3 decibels  
`Bass :: Up :: 3db`

Turn the vocals up 3db, **but only around 4k**  
`Vox :: Up :: 3db :: 4k`

Pan the lead guitar hard left  
`Lead Guitar :: Pan :: -100`

Cut Bob by 3db, but only around 250hz to 400hz  
`Bob :: Down :: 3db:: 220hz - 400hz`

Room Mic volume down the by 25%   
`Room :: Down :: 25%`

#### source

- instrument
- person
- entire mix
- microphone

#### actions

- Up
- Down
- Pan 
- Mute

#### amount

- decibels 3db
- percentage - 25%
- pan
    - -100 is hard left
    - 0 is center
    - 100 is hard right

#### frequency

- single integer (ie 4k or 4000)
- range ( 200hz to 400hz )

## General Guidelines

- Location engineer should confirm he/she applied the last change with an emoji thumbs up (expect at least 2 or 3 second delay)
- Remote engineer should confirm he/she is happy / can hear the change
- Avoid unnecessary chatter
