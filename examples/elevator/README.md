### Run example

**Features used:**
- Piping
- Multi model
- Model selection 
- Gif generation
- Gif special parameter
- Quiet mode

`clingo examples/elevator/encoding.lp examples/elevator/viz.lp examples/elevator/instance.lp --outf=2 | clingraph --gif --json --select-model=0 --dir='out/elevator' --gif-param="fps=1" -q`