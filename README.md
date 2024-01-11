## One day workshop on network science, with a focus on creating node-level features in multiplex networks using matrix multiplication

This webpage contains all the materials for a one-day workshop on network science. The materials on this website are [GNU General Public License v3.0](https://www.gnu.org/licenses/gpl-3.0.en.html) licensed.

## Course objectives

How can networks help us understand and predict social systems? This course introduces concepts and tools in network science. The objective of the course is that participants acquire hands-on knowledge on how to analyze different types of networks. Participants will be able to understand when a network approach is useful, understand different types of networks, understand the differences and similarities between a Complex Networks and a Social Network Analysis approach, describe network characteristics, creating node-level features in multiplex networks.

The course has a hands-on focus, with lectures accompanied by programming practicals (in Python) to apply the knowledge on real networks.


### Instructors
Javier Garcia-Bernardo (SoDa/UU) -- 2022, 2023
Eszter Bokányi (POPNET/UvA) -- 2022

### Folder structure
Slides: 
- Slides with the materials
Code:
- `1_intro_networks`: First practical on networkx
- `2_matrix_multiplication`: Second practical on matrix multiplication
- `3_popnet`: Third practical on matrix multiplication in the context of CBS data
- `z_lecture_simulations`: Creating some plots used during the lectures


### Prerequisites
1. Install anaconda/miniconda
2. Clone the repository
3. Install dependencies and start jupyter notebook
```
conda env create -f environment.yml
conda activate networks
jupyter notebook
```

## Contact

This project is developed and maintained by the [ODISSEI Social Data
Science (SoDa)](https://odissei-soda.nl/) team.

For questions about this course, you can contact us at [soda@odissei-data.nl](mailto:soda@odissei-data.nl), or you can contact the instructor Javier Garcia-Bernardo ([j.garciabernardo@uu.nl](mailto:j.garciabernardo@uu.nl))
