# chicken-egg-cffhackday

## What is this about?

it's a test repository to see if we can pre-reserve DOIs on zenodo (technically possible through their API) and then add the pre-released DOI to a zenodo.json schema before the release and thus the push from GitHub to Zenodo.

Turns out, we couldn't get zenodo to parse the pre-reserved DOI and it always created a new DOI for our releases.
