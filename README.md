# Source Data of SCALE

    git clone https://github.com/jsxlei/Source_Data
    cd Source_Data
      
Download following data under Source_Data dir:
* **data** [[Download]](https://cloud.tsinghua.edu.cn/f/2b6ee1c286bd45169fb2/?dl=1)  
* **result** [[Download]](https://cloud.tsinghua.edu.cn/f/9a3c05235683401d89d5/?dl=1)  
* **corrupt_data** [[Download]](https://cloud.tsinghua.edu.cn/f/c69ef5e5e97b436d90be/?dl=1)  
* **corrupt_result** [[Download]](https://cloud.tsinghua.edu.cn/f/ce107f2792a14b6b9494/?dl=1)  
* **simulate** [[Download]](https://cloud.tsinghua.edu.cn/f/e337aa1171e1491c95ea/?dl=1)

Decompression the gz file by tar -xzvf

    tar -xzvf data.tar.gz
    tar -xzvf result.tar.gz
    tar -xzvf corrupt_data.tar.gz
    tar -xzvf corrupt_result.tar.g
    tar -xzvf simulate.tar.gz
    
Install SCALE from github:

    git clone git://github.com/jsxlei/SCALE.git
    cd SCALE
    python setup.py install
    
Repeat the figures in the manuscript through the notebook. 
