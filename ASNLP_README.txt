Academia Sinica NLPLab Readme

1. install 'convert' command
	> sudo apt-get install imagemagick
	
2. get 'pylearn' library (only need random_weights class)
	http://deeplearning.net/software/pylearn/
	
	> hg clone http://hg.assembla.com/pylearn Pylearn
	
	and set the path to $PYTHONPATH
	
3. get Turian's utility libraries and neural-language-model (http://metaoptimize.com/projects/wordreprs/)
	You will need my common python library:
		http://github.com/turian/common
	and my textSNE wrapper for t-SNE:
		http://github.com:turian/textSNE
	You will need Murmur for hashing.
		easy_install Murmur	

4. get main codebase
	We will have a ported version for our environment (ToDo)
		https://github.com/AcademiaSinicaNLPLab/neural-language-model
	original version	
		https://github.com/turian/neural-language-model
		
	To train a monolingual language model, probably you should run:
		[edit hyperparameters.language-model.yaml]
		./build-vocabulary.py
		./train.py
	
	
	
	
