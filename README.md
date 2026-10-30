# pct-designsdatabase

Public icons and other public assets for the Printcraft Tees Brand Designs database in Notion.

Keep this repo public-safe: no pricing, costs, margins, credentials, or unreleased brand strategy. Private working docs live elsewhere.

## Notion page icons

Used by the n8n workflow "Brand Designs: Icon by Product Type". Each file is a 512 px transparent PNG, with the SVG source beside it.

| Notion row | Icon | URL |
|---|---|---|
| Record Type = Design | `design.png` | https://raw.githubusercontent.com/ccnickjoseph/pct-designsdatabase/main/icons/design.png |
| Product Type = T-Shirt | `tshirt.png` | https://raw.githubusercontent.com/ccnickjoseph/pct-designsdatabase/main/icons/tshirt.png |
| Product Type = Long Sleeve | `longsleeve.png` | https://raw.githubusercontent.com/ccnickjoseph/pct-designsdatabase/main/icons/longsleeve.png |
| Product Type = Tank | `tank.png` | https://raw.githubusercontent.com/ccnickjoseph/pct-designsdatabase/main/icons/tank.png |
| Product Type = Fleece Crewneck | `crewneck.png` | https://raw.githubusercontent.com/ccnickjoseph/pct-designsdatabase/main/icons/crewneck.png |
| Product Type = Fleece Hoodie | `hoodie.png` | https://raw.githubusercontent.com/ccnickjoseph/pct-designsdatabase/main/icons/hoodie.png |
| Product Type = Hat | `hat.png` | https://raw.githubusercontent.com/ccnickjoseph/pct-designsdatabase/main/icons/hat.png |

Do not rename or move these files. Notion stores the URL, so a rename breaks every icon that uses it. To change an icon, replace the file at the same path.

## Adding a new Product Type

1. Draw the icon in the same style (slate body, light rib details, 256 viewBox).
2. Add `icons/<name>.svg` and `icons/<name>.png` (512 px, transparent).
3. Add a line for it in the n8n workflow's icon map.
