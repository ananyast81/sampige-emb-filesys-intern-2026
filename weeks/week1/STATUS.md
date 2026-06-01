# Week 1 Status — 2026-05-25 to 2026-05-29

## Shipped
Created a 1 page diagram showing:
- How srv_phb_add_contact() flows down to storage today
- The three formats (RECORD / FILE / BINARY) and the four devices (FLASH / SIM1 / SIM2 / SD)
- Where the flash backend will plug in <br><br>
Commit hash: 3f6b254

## Slipped
- None

## Blockers
- Understood the overall idea of LittleFS, not really confident about implementation yet
- For flash, will we be using a partition table or will partition be hardcoded?
- Partition for each of the formats on flash is to be discussed
- What exactly is nv kv? Does it refer to records?

## Next week
- See `weeks/week2/README.md`

## Demo (Friday)
Flow of srv_phb_add_contact() down to SDL and HW flash.

## Notes for mentor
- NOR flash part number: GD25Q64 or W25Q64 (both are identical)
