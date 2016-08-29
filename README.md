webscreensaver
==============

A screen hack which uses WebKit and works with XScreensaver

dependencies
------------

 * python 2.7
 * xscreensaver
 * GTK3
 * webkitgtk

install
-------

Copy `webscreensaver` into `/usr/lib/xscreensaver` and then edit `~/.xscreensaver`:

    programs:
                  webscreensaver                  \n\

If you wish to set the url:

    -url <url_to_the_page_you_want>

Otherwise it will choose a random one.

You can persist cookies by specifying a cookie file:

    -cookie-file <path_to_cookie_file>

Available screensavers
----------------------

 * clock (http://freelance-html-developer.com/clock/)
 * noiseclock (https://www.yuichiroharai.com/wgl/4_noise_clock/)
 * water (http://oos.moxiecode.com/js_webgl/water_noise/)
 * fractal (http://david.alloza.eu/WebGL/morphing.html)
 * anaglyph (http://threejs.org/examples/webgl_effects_anaglyph.html)
 * pulpo (https://dl.dropboxusercontent.com/u/6983010/wserv/gexp_pulpo/index.html)
 * aquarium (http://webglsamples.org/aquarium/aquarium.html)
 * sea3d (http://threejs.org/examples/webgl_loader_sea3d.html)
 * marchingcubes (http://threejs.org/examples/webgl_marchingcubes.html)
 * billboards (http://threejs.org/examples/webgl_points_billboards_colors.html)
 * billboards2d (http://threejs.org/examples/webgl_points_billboards.html)
 * sprites (http://threejs.org/examples/webgl_points_sprites.html)
 * dof (http://threejs.org/examples/webgl_postprocessing_dof.html)
 * shader (http://threejs.org/examples/webgl_shader.html)
 * ibillboards (http://threejs.org/examples/webgl_buffergeometry_instancing_billboards.html),
 * molecules (http://threejs.org/examples/css3d_molecules.html)
 * # css3d_sprites (http://threejs.org/examples/css3d_sprites.html)
 * earth (http://threejs.org/examples/misc_controls_fly.html)
 * birds (http://threejs.org/examples/canvas_geometry_birds.html)
 * sky_panorama (http://threejs.org/examples/canvas_geometry_panorama.html)
 * particles_random (http://threejs.org/examples/canvas_particles_random.html)
 * particles_sprites (http://threejs.org/examples/canvas_particles_sprites.html)
 * lines_sphere (http://threejs.org/examples/webgl_lines_sphere.html)

TODO
----

 * In two monitors mode choose for first monitor defined screensaver
