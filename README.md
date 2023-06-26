# celebrityDetection

The workflow detects celebrities in a given set of images and creates collages of cropped faces for each celebrity, including a summary for the celebrity translated to German. The workflow contains 6 functions and two parallel loops.

## Functions

The functions should be deployed using `Python 3.7` as a runtime.

For GCP, no `detectCelebrities` function exists, since Google does not grant permissions to every user to access their celebrity recognition API.