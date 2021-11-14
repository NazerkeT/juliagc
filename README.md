## CS263 Project - Julia GC Inspection for Multhithreaded Programs 

### Week 1: Literature review 

Julia Tutorial Video: https://www.youtube.com/watch?v=sE67bP2PnOo&ab_channel=DerekBanas
<br />Julia Tutorial Set 1: http://www.newthinktank.com/2018/10/julia-tutorial/
<br />Julia Tutorial Set 2: https://techytok.com/from-zero-to-julia/

Garbage Collector(GC) Blog: https://wesselb.github.io/2020/11/23/julia-learning-circle-meeting-2.html

Memory Layout Documentation: https://docs.julialang.org/en/v1/devdocs/object/

GC tracing tools:
<br />
https://docs.julialang.org/en/v1.8-dev/devdocs/probes/#Available-probes
https://vchuravy.dev/notes/2021/08/bpftrace/
https://discourse.julialang.org/t/the-state-of-dataframes-jl-h2o-benchmark/43081/33\\https://github.com/JuliaLang/julia/pull/41616
https://github.com/JuliaLang/julia/pull/41616
https://goinbigdata.com/how-to-use-dtrace-on-mac-os-x/

### Week 2: Troubleshooting with tool installation
- VS Code and Julia Editor connection with Linux server.
- Installing Linux VirtualBox/Docker to Mac.

### Week 3: Troubleshooting with tools and initial simulations with `bpftrace`
- Establishing working environment with UTM Virtual Box and Parallels VM.
- Running a `julia_gc_alloc` uprobe on a test function following a tutorial with Julia's stable branch(v1.6.3):
https://vchuravy.dev/notes/2021/08/bpftrace/#a_note_on_ustack
- Troubleshooting `dtrace` tools and Julia's master branch installation(ongoing).
