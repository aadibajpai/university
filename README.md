# university request detection proof of concept

![proof of concept](poc.png)

find catchier title maybe

should detect university if you visit this from a university

imagine if I had this last year during college application szn

## API

URL: https://uni.aadibajpai.workers.dev

*status code 200* with university name as text body if found.

Else, *404 not found*

Eg. `{status: 200, "Columbia University"}` or `{status: 404, "not found"}`

No rate limits or anything, go wild.

## Example Usage

See [index.html](index.html)

I set it up for [my website](https://aadibajpai.com) too as a possible implementation to slightly modify text if
a university visitor is detected. 

Look at that [here](https://github.com/aadibajpai/my-website/blob/7a324aacc98563389bda868867fc17d7d20e1199/index.html#L341-L355).

## Isn't this overkill?

no u
