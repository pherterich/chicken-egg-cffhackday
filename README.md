# chicken-egg-cffhackday

## What is this about?

it's a test repository to see if we can pre-reserve DOIs on zenodo (technically possible through their API) and then add the pre-released DOI to a zenodo.json schema before the release and thus the push from GitHub to Zenodo. (Ideally with an in between step that creates a CFF file with all the information from the zenodo.json)

Turns out, we couldn't get zenodo to parse the pre-reserved DOI and it always created a new DOI for our releases.

You could probably achieve this by pre-reserving the DOI, creating the .zenodo.json file and the CFF file for the GitHub repo and then pushing all this through the API to zenodo an upload the release tarball as a "standard" file upload instead of using the GitHub integration.
