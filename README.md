# A Novel Deep Unsupervised Learning Method for Sum-Rate Optimization in Device-to-Device Networks with a Quality-of-Service Constraint

## Project Description
This project introduces a new Deep Unsupervised Learning (DUL) approach based on an optimization problem with box constraints coupled with polytope constraints for maximizing the sum rate in Device-to-Device (D2D) networks, a key factor in enhancing network capacity and efficiency. Current deep learning methods struggle with managing resource-intensive projection steps and need multiple iterations to optimize the sum rate in varying D2D environments. The proposed approach overcomes these challenges by minimizing the loss function and satisfying constraints when dealing with a monotone matrix. The novel approach controls transmit power through a fully connected, multi-layer Deep Neural Network (DNN), solving the complex, non-convex optimization problem associated with optimizing the sum rate in a symmetric interference channel model. The result shows that this method outperforms other power control methods regarding average sum rate, hit rate, and complexity when applied to a standard symmetric K-user Gaussian interference channel.

## Feasible Datasets for the Transmission Channel Parameters
In total, 55 feasible different datasets have been generated to analyze the model’s performance, which totals 22.1 GB.

Link for datasets: https://1drv.ms/f/s!ApktXr3Tu2RWgtQPgQM8qhtPgzYmgw?e=KNdtfu

There are three groups of datasets, as follows:
1. Dataset Group A: 35 datasets for K = 5, EsN0 = [0 dB, 10 dB, 20 dB, 30 dB, 40 dB, 50 dB, 60 dB], and five scenarios of SINRmin = 0.5. The total size of these datasets is 11.1 GB.
2. Dataset Group B: 20 datasets in total for EsN0 = [0 dB, 10 dB, 20 dB, 30 dB, 40 dB] for each K = [5, 6, 7, 8], with all SINRmin = 0.2, e.g., for K = 5, SINRmin = [0.2, 0.2, 0.2, 0.2, 0.2]. The total size of these datasets is 11 GB.
3. Dataset Group C: 25 datasets out of 35 datasets from Group A, i.e., K = 5, and five scenarios of SINRmin = 0.5 but EsN0 = [0 dB, 10 dB, 20 dB, 30 dB, 40 dB]

## List of files
- README.md : README file
- Project Presentation.pdf : Slides for presentations

## References
1. B. Acharjee, M. Hanif and O. Waqar, "Deep Unsupervised Learning for Optimization With Box and Monotone-Matrix Based Polytope Constraints: A Case-Study of D2D Wireless Networks," in IEEE Wireless Communications Letters, doi: 10.1109/LWC.2023.3316114; https://ieeexplore.ieee.org/document/10251980.
2. Weblink for the thesis report: https://arcabc.ca/islandora/object/tru%3A6263?solr_nav%5Bid%5D=812994808783a9d1ed2a&solr_nav%5Bpage%5D=4450&solr_nav%5Boffset%5D=7
