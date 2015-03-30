Thinking Grids
==============

A study guide for understanding Grids with working examples implemented in CSS3, Less, Sass, Stylus, and [Postcss](https://github.com/postcss/postcss). 

Libraries:

- [Bootstrap](http://getbootstrap.com) (less)
- [Flexbox](http://flexboxgrid.com) (css3+postcss)
- [Frameless](http://framelessgrid.com) (less)
- [Gridism](http://cobyism.com/gridism/) (css3+postcss)
- [Skel](https://github.com/n33/skel) (sass)
- [Lost](https://github.com/corysimmons/lost) (stylus)
- [Susy](http://susy.oddbird.net) (sass)

## Workflow

The workflow is optimized for rapid prototyping.

Templates are written in plain HTML5. Styles are written in either CSS3 with Postcss, Less, or Sass, based
on the libraries. Npm itself is used as a build tool (no build tools please) and Bower is used to
manage dependencies.

To start a live reloading server that compiles all preprocessors and postprocesors, run:

	npm start

Preview the page at `http://127.0.0.1:8000` and start designing.

## Credits

The initial HTML templates and styles were ported from the examples of respective libraries. Redundant 
styles were removed to focus on grids. 

## Book

I'm writing a brief book on Grids and will update this space soon.

## References

### Articles

- [Baseline Grids](http://alistapart.com/article/settingtypeontheweb)
- [CSS Grid Module Level 1 Spec](http://dev.w3.org/csswg/css-grid/)
- [Don't overthink it Grids](https://css-tricks.com/dont-overthink-it-grids/)
- [Fluid Grids](http://alistapart.com/article/fluidgrids)
- [Golden Grid System](http://goldengridsystem.com)
- [OOCS](http://oocss.org/grids_docs.html)
- [The magic behind Bootstrap Grids](http://www.helloerik.com/the-subtle-magic-behind-why-the-bootstrap-3-grid-works)
- [Understanding Susy's Grids](http://www.zell-weekeat.com/susy2-tutorial)

### Other Libraries

- [Bobcss](http://bbo-code.com/bobscss)

## License

Copyright (c) 2015 Priyatam Mudivarti, and original authors of libraries.

[MIT](http://opensource.org/licenses/MIT).
