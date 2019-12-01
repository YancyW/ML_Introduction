#env setting
## install conda, activate a new environment
## install cuda tookit, tf and keras
	'''
	conda create -n tensorflow_gpuenv tensorflow-gpu 
	conda install keras
	'''  
## install pytorch
    '''
	conda create -n pytorch python=3.7 
    conda install pytorch torchvision cudatoolkit=10.1 -c pytorch
    '''
