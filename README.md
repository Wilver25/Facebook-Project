#Facebook Proyect

Estructura:

1. Código html.
2. Creacion de un css (`estilo para la visualizacion del programa`)
3. Commit your changes (`git commit -am "Added Snarkdown"`)
4. Push to the branch (`git push origin my_markup`)
5. Open a [Pull Request][1]
6. Enjoy a refreshing Diet Coke and wait
7. Release


If you are the current maintainer of this gem:

0. Bump the version number in `lib/github-markup.rb`, adhering to [Semantic Versioning](https://github.com/Wilver25/Facebook-Project/blob/master/index.html)
0. Update `HISTORY.md`
0. Test the latest version on GitHub
  0. Build the new version with `rake build`
  0. Copy `pkg/github-markup*.gem` to `vendor/cache` in your local checkout of GitHub
  0. Update the version for `github-markup` in the `Gemfile`
  0. Run `bundle update --local github-markup`
  0. Run any relevant tests and test it manually from the browser.
0. Push the new gem release with `rake release`. If you don't have permission to release to rubygems.org, contact one of the existing owners (`gem owners github-markup`) and ask them to add you.
