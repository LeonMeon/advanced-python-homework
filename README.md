# Advanced python homework

Before perform of new homework assignment merge top commit of main branch in your repository.

# Development installation

Just use

'''
<<<<<<< HEAD
conda env create -f env.yml 
=======
conda create --name ENV_NAME
>>>>>>> origin/main
'''

then run it  by 

'''
conda activate stem_env
'''

If there's need to  install in editable mode:

'''
cd ./stem_framework
pip install -e .
'''

# Documentation by Sphinx

'''
python setup.py build_sphinx
'''



