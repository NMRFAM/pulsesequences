# Pulse Sequences for Bruker Systems

| Pulse Sequence                                     | Description                                | Topspin |Reference      |
|----------------------------------------------------|--------------------------------------------|---------|---------------|
| [sr_noesy-hsqc.cd](sr_noesy-hsqc.cd)               | Super-Resolution NOESY-HSQC 3D             | 3.1+    | [1](#ref1)    |
| [hsqcetfpf3gpsi2_slf.jll](hsqcetfpf3gpsi2_slf.jll) | Hybrid NMR SLF-HSQC 3D                     | 3.1+    | [2](#ref2)    |
| [hnco_slf.jll](hnco_slf.jll)                       | Hybrid NMR SLF-HNCO 3D/4D                  | 3.1+    | [2]($ref2)    |

## Installation

On your spectrometer computer, change to the directory containing your user pulse sequences. For example,
on Topspin 3.2 this directory might be:

```shell
cd /opt/topspin3.2/exp/stan/nmr/lists/pp/user/
```

Clone the repository with ``git``:

```shell
git clone https://github.com/NMRFAM/pulsesequences.git
```


## References
<a name="ref1">1</a>: Lorieau JL. (2019) Partial alignment, residual dipolar couplings and molecular symmetry in solution NMR. J. Biomol. NMR. 73: 477-491. doi: [10.1007/s10858-019-00256-2](http://doi.org/10.1007/s10858-019-00256-2)

<a name="ref2">2</a>: Thiagarajan-Rosenkranz P, Draney AW, Lorieau JL. (2017) Hybrid NMR: A Union of Solution- and Solid-State NMR. J. Am. Chem. Soc. 139(13): 4715-4723. doi: [10.1021/jacs.6b11402](http://doi.org/10.1021/jacs.6b11402)
