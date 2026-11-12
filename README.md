# bishopadbyrd.org

Official site of the Rt. Rev. Alex D. Byrd: Founding Pastor of Living Faith Covenant Church, Episcopal Assistant to the Presiding Prelate of The Fellowship of Affirming Ministries (TFAM), and Regional Vice President with Primerica.

A static site with no build step. Every page is plain HTML and CSS.

## Pages

| Path | Page |
|---|---|
| `/` | Home: hero, three callings, About, news and media archive, Stay Connected, Episcopal Office |
| `/ecard/` | Digital calling card for the Episcopal Office |
| `/privacy/` | Privacy Statement |
| `/terms/` | Terms Of Use |
| `/VirtualBoardRoom/` | Redirect to the Virtual Board Room Zoom meeting (`/virtualboardroom/` also works) |
| `/BishopAlexByrd.vcf` | Episcopal vCard (includes the Bishop's crest) |

## Folders

- `assets/` holds the images: the portrait, the Bishop's seal (`bishop-seal.png` is the full-size original), favicons, the TFAM logos, and the footer photo.
- `_extras/` holds related work that is not part of the public site. GitHub Pages does not publish folders that start with an underscore.
  - `alexdbyrd-net/` contains the redesigned Primerica scheduler page for alexdbyrd.net.
  - `youtube-banners/` contains the 2560×1440 channel banners for Vocal Grace and Living Faith.

## Publishing with GitHub Pages

1. Open **Settings → Pages**, choose **Deploy from a branch**, and select `main` / root.
2. Under **Custom domain**, enter `bishopadbyrd.org`, then turn on **Enforce HTTPS** once it becomes available.
3. At the domain registrar, point DNS to GitHub Pages: four `A` records for the apex (`185.199.108.153`, `185.199.109.153`, `185.199.110.153`, `185.199.111.153`) and a `CNAME` for `www` pointing to `revadbyrd.github.io`.

## Credits

- Designed by [Red Boot LLC](https://redbootllc.com/website-launch).
- Footer photo by Naassom Azevedo on Unsplash.
