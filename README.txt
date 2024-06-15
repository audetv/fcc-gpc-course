(base) D:\>e:

(base) E:\>cd "Python Testing"

(base) E:\Python Testing>ls
fcc-gpt-course

(base) E:\Python Testing>python -m venv cuda

(base) E:\Python Testing>cuda\Scripts\activate

(cuda) (base) E:\Python Testing>

(cuda) (base) E:\Python Testing>pip3 install matplotlib numpy pylzma ipykernel jupyter

https://visualstudio.microsoft.com/ru/visual-cpp-build-tools/

https://pytorch.org/

(cuda) (base) E:\Python Testing>pip3 install torch torchvision torchaudio --index-url https://download.pytorch.org/whl/cu121

(cuda) (base) E:\Python Testing\fcc-gpt-course>jupyter notebook

(cuda) (base) E:\Python Testing\fcc-gpt-course>python -m ipykernel install --user --name=cuda --display-name "cuda-gpt"
Installed kernelspec cuda in C:\Users\audet\AppData\Roaming\jupyter\kernels\cuda