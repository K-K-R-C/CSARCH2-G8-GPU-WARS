# CSARCH2-G8-GPU-WARS

**Title**: GPU Wars: Five Turning Points That Changed Computing  
**GitHub Link**: 

### Group Members
* BENDOL, Trisha Mae R.
* CAMATO, Karl Kristoffer R.
* DESCALZO, Alberto Miguel T.
* GREGORIO, John Marc Joepherl M.
* MARTIN, Kurt Nehemiah Z.

## Topic Theme
Every frame rendered in a video game, every AI-generated image and every large language model relies on a technology that was originally designed for a much simpler purpose: drawing graphics faster.

The Graphics Processing Unit (GPU) has undergone one of the most significant architectural transformations in computing history. What began as dedicated hardware for 3D graphics evolved into a massive computing platform that powers artificial intelligence, scientific simulations and modern super computers.

This exhibit explores five major turning points that shaped the evolution of the GPU and examines how it became one of the most important technologies in modern computing.

## Tech Stack
### Frontend Technologies
| Technology  | Role |
| ------------- | ------------- |
| Astro 6 | Primary framework for exhibit development and integration with the museum website  |
| React (JSX) | Interactive educational components and visualizations  |
| MDX | Combines exhibit content with embedded React components  |
| CSS | Styling, animations and responsive layouts  |

* **Astro 6**
  
Astro will serve as the foundation of the virtual exhibit. It provides compatibility with the museum template, while also allowing for interactive React components to be integrated within MDX content.

Planned uses:
1. Exhibit page rendering
2.  Component integration
3. Static site generation

* **React (JSX)**
  
React will be used to build the interactive elements that allow visitors to explore GPU history and architecture.

Planned uses:
1. Interactive Timeline
2. GPU Architecture Explorer
3. GPU Generation Comparison Tool

* **MDX**
  
MDX will be used to combine written explanations with interactive components in a seamless exhibit format.

It will support:
1. Historical Narratives
2. Technical explanations
3. Embedded interactive visuals

* **CSS**
  
CSS will be used to create a modern digital museum aesthetic inspired by GPU hardware and computing systems.

Design features include:
1. Dark-themed interface
2. Card-based layouts
3. Smooth transitions and animations
4. Responsive desktop/mobile design

---

### Backend Technologies
| Technology  | Role |  
| ------------- | ------------- |
| Node.js  |  Ensures compatibility with modern JavaScript tooling and supports deployment of the exhibit website.  |
| Express  | Will only be used if needed for additional functionality in future development.  |

* **Node.js**
  
Node.js will be used as the local runtime environment required by Astro for development and build processes.

* **Express**
  
Possible uses:
1. Storing user interaction data (e.g., GPU comparison results)
2. Logging exploration activity
3. Supporting future expansion of interactive components


## I. Exhibit Narrative
### 1.) Introduction: The Rise of GPU
   
Today, GPUs power video games, artificial intelligence, and scientific simulations. However, they were originally designed to solve a much narrower problem: rendering graphics efficiently.

This exhibit explores how that specialized hardware evolved into one of the most important computing platforms in modern history.

### 2.) Before Dedicated Graphics Hardware
Before GPUs existed, all graphics processing was handled by the CPU. 

Topics covered include:
* CPU-based rendering
* Software rasterization
* Performance bottlenecks
* Increasing demand for 3D graphics
  
**Key Idea**:
As graphical demands increased, general-purpose CPUs became insufficient for real-time rendering workloads.


### 3.) Five Turning Points in GPU History
This section is the core of the exhibit and is presented as an interactive timeline.

#### a. Turning Point #1 - 1996
*3dfx Voodoo Graphics*
- First widely successful consumer 3D accelerator

#### b. Turning Point #2 - 1999
*GeForce 256*
- Introduction of the “GPU” concept with hardware transform and lightning

#### c. Turning Point #3 - 2007
*CUDA*
- GPUs become general-purpose parallel computing devices

#### Turning Point #4 - 2018
*RTX 20 Series*
- Introduction fo ray tracing and AI-assisted rendering hardware

#### Turning Point #5 - 2022-Present
*AI Supercomputing Era*
- GPU’s become core infrastructure for AI training and interference


## II. Interactive Component

## III. Proposed Design Layout

## IV. Planned JSX Components (???)
