Just removing the Chinese for probably just as broken or in accurate English, but it's getting there.

Paddle Quantum
Paddle Quantum (quantity paddle) is a quantum machine learning tool set developed based on Baidu flying paddle, supports the construction and training of quantum neural networks, provides easy-to-use quantum machine learning development kits and quantum optimization, quantum chemistry and other cutting-edge quantum application tool sets, This makes Baidu Flying Paddle the first and only deep learning framework that supports quantum machine learning in China.



Gauge builds a bridge between artificial intelligence and quantum computing, not only can quickly realize the construction and training of quantum neural networks, but also provide easy-to-use quantum machine learning development kits and quantum optimization, quantum chemistry and other cutting-edge quantum application tool sets, and provide Many self-developed quantum machine learning applications. With Baidu flying paddle deep learning platform energizing sub-computing, measuring paddle provides powerful support for scientific researchers and developers in the field to easily develop quantum artificial intelligence applications, and also provides a feasible way for the majority of quantum computing enthusiasts. Learning path.

Features
Ease of use: Provide simple neural network construction and rich quantum machine learning cases.
Versatility and expandability: support common quantum circuit models and provide multiple optimization tools
Featured tool set: Provides quantum optimization, quantum chemistry and other cutting-edge quantum application tool sets, and self-developed multiple quantum machine learning applications.
installation steps
Install PaddlePaddle
Please refer to the PaddlePaddle installation and configuration page. This project requires PaddlePaddle 1.8.0 or higher.

Download and install Paddle Quantum
git clone http://github.com/PaddlePaddle/quantum
cd quantum
pip install -e .
Or use requirements.txt to install dependencies
python -m pip install --upgrade -r requirements.txt
Use openfermion to read the xyz description file (can only be installed and used under linux)
In VQE, call openfermion to read and calculate the molecular xyz file, so you need to install openfermion and openfermionpyscf.

pip install openfermion
pip install openfermionpyscf
run
cd paddle_quantum/QAOA/example
python main.py
Getting started and development
Getting started
Quantum computing is a new computing model formed by the intersection of quantum mechanics and computing theory. It has powerful information processing advantages and broad application prospects. It is regarded as the heart of future computing technology. For related introduction and introductory knowledge of quantum computing, please refer to [1-3].

Quantum machine learning is a cross-discipline that combines quantum computing and machine learning. On the one hand, it uses the information processing advantages of quantum computing to promote the development of artificial intelligence. On the other hand, it also uses the existing artificial intelligence technology to break through the bottleneck of quantum computing research and development. For introductory information about quantum machine learning, please refer to [4-6]. Paddle Quantum has established a bridge between artificial intelligence and quantum computing, providing strong support for research and development in the field of quantum machine learning, as well as providing rich cases for developers to learn.

Case introduction
In particular, we provide cases covering various fields such as quantum optimization, quantum chemistry, and quantum machine learning for everyone to learn. such as:

Quantum approximate optimization (QAOA), after completing the installation steps, open tutorial\QAOA.ipynb to study and learn.
cd tutorial
jupyter notebook QAOA.ipynb
Quantum feature solver (VQE), after completing the installation steps, open tutorial\VQE.ipynb to study and learn.
cd tutorial
jupyter notebook  VQE.ipynb
Development
Paddle Quantum is installed using the develop mode of setuptools, and related code modification can be directly entered into the paddle_quantumfolder to modify. The python file carries self explanatory notes.

Communication and feedback
We welcome you to submit questions, reports and suggestions through Github Issues .

QQ technical exchange group: 1076223166

Working with Paddle Quantum
We very much welcome developers to use Paddle Quantum for R&D of quantum machine learning. If you use Paddle Quantum for your work, please feel free to contact us. The representative work currently using Paddle Quantum regarding Gibbs state preparation is as follows:

[1] Youle Wang, Guangxi Li, and Xin Wang. 2020. Variational quantum Gibbs state preparation with a truncated Taylor series. arXiv2005.08797. [ pdf ]

Copyright and License
Paddle Quantum uses the Apache-2.0 license .

References
[1] Quantum Computing-Baidu Encyclopedia

[2] Michael A Nielsen and Isaac L Chuang. 2010. Quantum computation and quantum information. Cambridge university press.

[3] Phillip Kaye, Raymond Laflamme, and Michele Mosca. 2007. An Introduction to Quantum Computing.

[4] Jacob Biamonte, Peter Wittek, Nicola Pancotti, Patrick Rebentrost, Nathan Wiebe, and Seth Lloyd. 2017. Quantum machine learning. Nature 549, 7671, 195–202. [ pdf ]

[5] Maria Schuld, Ilya Sinayskiy, and Francesco Petruccione. 2015. An introduction to quantum machine learning. Contemp. Phys. 56, 2, 172–185. [ pdf ]

[6] Marcello Benedetti, Erika Lloyd, Stefan Sack, and Mattia Fiorentini. 2019. Parameterized quantum circuits as machine learning models. Quantum Sci. Technol. 4, 4, 043001. [ pdf ]
