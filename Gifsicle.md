<pre>'Gifsicle' manipulates GIF images. Its most common uses include combining single images into animations, adding transparency, optimizing animations for space, and printing information about GIFs.

Mode options: at most one, before any filenames.
  -m, --merge                   Merge mode: combine inputs, write stdout.
  -b, --batch                   Batch mode: modify inputs, write back to
                                same filenames.
  -e, --explode                 Explode mode: write N files for each input,
                                one per frame, to 'input.frame-number'.
  -E, --explode-by-name         Explode mode, but write 'input.name'.

General options: Also --no-OPTION for info and verbose.
  -I, --info                    Print info about input GIFs. Two -I's means
                                normal output is not suppressed.
      --color-info, --cinfo     --info plus colormap details.
      --extension-info, --xinfo --info plus extension details.
  -V, --verbose                 Prints progress information.
  -h, --help                    Print this message and exit.
      --version                 Print version number and exit.
  -o, --output FILE             Write output to FILE.
  -w, --no-warnings             Don't report warnings.
      --conserve-memory         Conserve memory at the expense of speed.
      --multifile               Support concatenated GIF files.

Frame selections:               #num, #num1-num2, #num1-, #name

Frame change options:
  --delete FRAMES               Delete FRAMES from input.
  --insert-before FRAME GIFS    Insert GIFS before FRAMES in input.
  --append GIFS                 Append GIFS to input.
  --replace FRAMES GIFS         Replace FRAMES with GIFS in input.
  --done                        Done with frame changes.

Image options: Also --no-OPTION and --same-OPTION.
  -B, --background COL          Make COL the background color.
      --crop X,Y+WxH, --crop X,Y-X2,Y2
                                Crop the image.
      --crop-transparency       Crop transparent borders off the image.
      --flip-horizontal, --flip-vertical
                                Flip the image.
  -i, --interlace               Turn on interlacing.
  -S, --logical-screen WxH      Set logical screen to WxH.
  -p, --position X,Y            Set frame position to (X,Y).
      --rotate-90, --rotate-180, --rotate-270, --no-rotate
                                Rotate the image.
  -t, --transparent COL         Make COL transparent.

Extension options: Also --no-OPTION and --same-OPTION.
  -x, --app-extension N D       Add an app extension named N with data D.
  -c, --comment TEXT            Add a comment before the next frame.
      --extension N D           Add an extension number N with data D.
  -n, --name TEXT               Set next frame's name.

Animation options: Also --no-OPTION and --same-OPTION.
  -d, --delay TIME              Set frame delay to TIME (in 1/100sec).
  -D, --disposal METHOD         Set frame disposal to METHOD.
  -l, --loopcount[=N]           Set loop extension to N (default forever).
  -O, --optimize[=LEVEL]        Optimize output GIFs.
  -U, --unoptimize              Unoptimize input GIFs.

Whole-GIF options: Also --no-OPTION.
      --careful                 Write larger GIFs that avoid bugs in other
                                programs.
      --change-color COL1 COL2  Change COL1 to COL2 throughout.
  -k, --colors N                Reduce the number of colors to N.
      --color-method METHOD     Set method for choosing reduced colors.
  -f, --dither                  Dither image after changing colormap.
      --resize WxH              Resize the output GIF to WxH.
      --resize-width W          Resize to width W and proportional height.
      --resize-height H         Resize to height H and proportional width.
      --scale XFACTOR[xYFACTOR] Scale the output GIF by XFACTORxYFACTOR.
      --transform-colormap CMD  Transform each output colormap by shell CMD.
      --use-colormap CMAP       Set output GIF's colormap to CMAP, which can
                                be 'web', 'gray', 'bw', or a GIF file.
</pre>
