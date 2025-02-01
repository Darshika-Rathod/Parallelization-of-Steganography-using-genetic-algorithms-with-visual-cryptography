# Parallelization-of-Steganography-using-genetic-algorithms-with-visual-cryptography

Overview-
This project explores the parallelization of steganography using genetic algorithms and visual cryptography. The approach enhances the security of hidden information while optimizing computational efficiency through parallel processing techniques.

Features
1) Parallelization: Accelerates the encoding and decoding processes.
2)Genetic Algorithms: Optimizes the steganographic embedding process.
3)Visual Cryptography: Ensures secure data hiding and retrieval.
4)High Performance Computing (HPC): Implements parallel execution to improve speed and scalability.

Technologies Used
1)C
2)OpenMP/MPI for parallel processing
3)OpenCV 
4)CUDA

Installation
1)Clone the repository:
git clone https://github.com/yourusername/Parallel-Steganography.git
cd Parallel-Steganography
2)Compile the project:
make

Usage
1)Encoding: Hide a secret message inside an image using genetic algorithms.
./encode input.png "Secret Text" output.png
2)Decoding: Retrieve the hidden message from the stego-image.
./decode output.png
3)Visual Cryptography Sharing: Generate shares for the hidden message.
./generate_shares output.png 2

Performance Optimization
1)Implements OpenMP/MPI for parallel execution.
2)Uses GPU acceleration (CUDA) for genetic algorithm optimization.
3)Reduces processing time significantly through HPC techniques.

Applications
1)Secure Communication: Protects sensitive data through steganographic techniques.
2)Digital Watermarking: Embeds invisible security marks in images.
3)Cryptographic Security: Enhances data privacy with visual cryptography.

Future Enhancements
1)Implement deep learning models to further enhance security.
2)Optimize parallelization with distributed computing frameworks.
3)Extend support for video steganography.
