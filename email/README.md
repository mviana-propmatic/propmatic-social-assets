# email/

Images that email signatures load by URL. Gmail strips images embedded in a
signature, so the signature generator on the internal North Star site
(Brand, Email signature) points at these files through jsDelivr, pinned to
the commit that added them:

    https://cdn.jsdelivr.net/gh/mviana-propmatic/propmatic-social-assets@<commit>/email/propmatic-signature-logo.png

Never edit or delete a file here once signatures use it. To change the logo,
add a new file with a new name and point the generator at it.

The source is rendered by northstar/build_brand.py in propmatic-content-system.
