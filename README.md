# Sleiv – offentlige sider

Offentlige sider for iOS-appen Sleiv, publisert med GitHub Pages.

| Side | Fil | URL |
| --- | --- | --- |
| Forside / support | `index.html` | https://kristofferchr.github.io/sleiv/ |
| Personvern | `privacy/index.html` | https://kristofferchr.github.io/sleiv/privacy/ |

Sidene er ren HTML uten byggesteg. `.nojekyll` gjør at GitHub Pages serverer
filene som de er.

## Publisering

Første gang: **Settings → Pages → Build and deployment**

- Source: **Deploy from a branch**
- Branch: **main**, mappe **/ (root)** → **Save**

Deretter publiseres hver push til `main` automatisk etter et minutt eller to.

## Bruk i App Store Connect

- **Privacy Policy URL**: `https://kristofferchr.github.io/sleiv/privacy/`
- **Support URL** (kreves ved App Store-release): `https://kristofferchr.github.io/sleiv/`

## Oppdatering

Endre filene og push til `main`. Ved endringer i personvernerklæringen:
oppdater datoen «Sist oppdatert» på både norsk og engelsk.

Personvernerklæringen beskriver en app der alt lagres lokalt. Den må skrives
om før innlogging, synkronisering eller abonnement tas i bruk.
