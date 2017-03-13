# TMB Saint Aunes Jekyll Web site

Based on http://bencentra.github.io/centrarium/, thanks to bencentra

## Contributing

Want to help make this site even better? Contributions from the community are welcome!

Please follow these steps:

1. Fork/clone this repository.
3. Open a pull request on GitHub. A description and/or screenshot of changes would be appreciated!

## Run locally

Bash : 

`sudo docker run --label=jekyll --volume=$(pwd):/srv/jekyll -it -p 127.0.0.1:4000:4000 jekyll/jekyll jekyll serve`

Fish : 

`sudo docker run --label=jekyll --volume='pwd':/srv/jekyll -it -p 127.0.0.1:4000:4000 jekyll/jekyll jekyll serve`

## License

MIT. See [LICENSE.MD](https://github.com/tgirard12/tmbsa/blob/master/LICENSE.md).
