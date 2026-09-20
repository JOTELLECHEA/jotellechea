## Jonathan Tellechea

Physicist working in machine learning. Los Angeles.

Six years in experimental high-energy physics — ttHH searches at SCIPP, MIP
Timing Detector work at UVA — now building and probing neural networks. I'm
interested in what models learn that nobody told them to learn, and in
whether the uncertainty on a prediction means what it claims to mean.

**Current work**
- **[chess-transformer](https://github.com/JOTELLECHEA/chess-transformer)** —
  legal-move generation is neither capacity-bound nor data-bound alone; each
  roughly doubles fully-legal games, both together take it from 4.4% to 51.8%.
  Linear probing the residual stream shows the 12-layer model's board
  representation peaks three layers before the output
- **[schrodinger-pinn](https://github.com/JOTELLECHEA/schrodinger-pinn)** —
  modular PyTorch framework solving Schrödinger equation variants; hybrid
  Adam + L-BFGS optimization reached 0.0002% relative error on the 1D ground
  state energy
- **[gpt-from-scratch](https://github.com/JOTELLECHEA/gpt-from-scratch)** —
  epoch-boundary validation hid the loss minimum by 5,300 steps; step-interval
  evaluation cut val loss 1.63 → 1.46
- **[resume-tailor](https://github.com/JOTELLECHEA/resume-tailor)** —
  role-specific résumés from a master document and a job posting; started as
  RAG, ended as full-context injection once retrieval proved wrong for a
  single-document corpus
- **Diffusion from the ground up** *(in progress)* — rebuilding DDPM from
  Ho et al. 2020 in stages, working toward a calorimeter fast-simulation
  surrogate

**Tools** PyTorch · Python · C++ · ROOT/uproot · Docker

**Publication** [Aromatic Copper Hydride Cages](https://zenodo.org/records/21768443), AAAFM Energy 2020;1(1):16–26 — first author

**Elsewhere** [jonathantellechea.com](https://jonathantellechea.com)

Open to research engineer and applied scientist roles.
