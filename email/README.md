# email/

Images that email signatures load by URL. Gmail strips images embedded in a
signature, so the signature generator on the internal North Star site
(Brand, Email signature) points at these files through jsDelivr, pinned to
the commit that added them:

    https://cdn.jsdelivr.net/gh/mviana-propmatic/propmatic-social-assets@<commit>/email/propmatic-signature-logo-tile.png

Never edit or delete a file here once signatures use it. To change the logo,
add a new file with a new name and point the generator at it.

The source is rendered by northstar/build_brand.py in propmatic-content-system.

Files:

- `propmatic-signature-logo-tile.png` is current: the wordmark inside a white
  rounded tile with padding, so it keeps its margin when Gmail's dark mode
  darkens the message around it.
- `propmatic-signature-logo.png` is the first version, kept because
  signatures pasted before the tile still point at it.
