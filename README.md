Learning Grids
==============

A study guide with working samples of Grids implemented in CSS3, Less, Sass, and CSS4 polyfills like Rework & Postcss.

Libraries:

- [Bootstrap](http://getbootstrap.com) (less)
- [Frameless](http://framelessgrid.com) (less)
- [Gridism](http://cobyism.com/gridism/) (css3+postcss)
- [Flexbox](http://flexboxgrid.com) (css3+postcss)
- [Skel](https://github.com/n33/skel) (sass)
- [Susy](http://susy.oddbird.net) (sass)

## Workflow

The workflow is optimized for rapid prototyping.

Templates are written in plain HTML5. Styles are written in either CSS3 with Postcss, Less or Sass, based
on the libraries. Npm itself is used as a build tool (no more build tools, please) and Bower is used to
manage dependencies.

To start live reloading server that compiles all preprocessors and postprocesors, run:

	npm start

Preview page at `http://127.0.0.1:8000` and start designing.

## Credits

The initial HTML templates and styles were ported from the examples of respective libraries. I've
removed unncessary styles to focus on examples using just grids. In addition, I would like to thank
the following fine designers have helped me understand how grids work in general, and css-grid libraries
in particular:

- [AJ](http://n33.co)
- [Joni Korpi](http://www.jonikorpi.com)
- [Zell Weekat](http://www.zell-weekeat.com/susy2-tutorial)

## License

Copyright (c) 2015 Priyatam Mudivarti, and original authors of libraries.

[MIT](http://opensource.org/licenses/MIT).
