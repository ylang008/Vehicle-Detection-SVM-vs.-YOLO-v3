# Vehicle-Detection-SVM-vs.-YOLO-v3

## the original video

https://user-images.githubusercontent.com/56523281/179372797-c19f9224-c374-4cf7-acb0-ff2963c02382.mp4

## 1-demo=1, the image of test for SVM pipeline and YOLO v3 pipeline

![Figure 2022-07-16 151135](https://user-images.githubusercontent.com/56523281/179373458-be6330b7-5c40-42af-8021-c85a3103e655.png)
![Figure 2022-07-16 151208](https://user-images.githubusercontent.com/56523281/179373467-792fc549-129e-4478-8fb5-6fbfceb3caf1.png)

## 2-demo=2, the video result of YOLOv3 pipeline

https://user-images.githubusercontent.com/56523281/179372781-660daf9d-a870-4cfa-8ac4-d6d59288710b.mp4

## 3-demo=3, the video result of SVM pipeline

https://user-images.githubusercontent.com/56523281/179373656-fdd94914-7f04-460d-9fb0-929ea0b07121.mp4

environment package list：
```python
Package                       Version
----------------------------- ---------
absl-py                       1.1.0
aiohttp                       3.8.1
aiosignal                     1.2.0
alabaster                     0.7.12
appdirs                       1.4.4
arrow                         1.2.2
astor                         0.8.1
astroid                       2.6.6
astunparse                    1.6.3
async-timeout                 4.0.1
asynctest                     0.13.0
atomicwrites                  1.4.0
attrs                         21.4.0
autopep8                      1.6.0
Babel                         2.9.1
backcall                      0.2.0
bcrypt                        3.2.0
beautifulsoup4                4.11.1
binaryornot                   0.4.4
black                         19.10b0
bleach                        4.1.0
blinker                       1.4
brotlipy                      0.7.0
cached-property               1.5.2
cachetools                    5.2.0
certifi                       2022.6.15
cffi                          1.15.0
chardet                       4.0.0
charset-normalizer            2.0.4
click                         8.0.4
cloudpickle                   2.0.0
colorama                      0.4.5
cookiecutter                  1.7.3
cryptography                  37.0.1
cycler                        0.11.0
debugpy                       1.5.1
decorator                     4.4.2
defusedxml                    0.7.1
diff-match-patch              20200713
docutils                      0.18.1
entrypoints                   0.4
fastjsonschema                2.15.1
flake8                        3.9.2
flatbuffers                   1.12
fonttools                     4.34.4
frozenlist                    1.2.0
gast                          0.4.0
google-auth                   2.9.1
google-auth-oauthlib          0.4.6
google-pasta                  0.2.0
grpcio                        1.47.0
h5py                          3.1.0  <--
idna                          3.3
imageio                       2.19.3
imageio-ffmpeg                0.4.7  <--
imagesize                     1.4.1
importlib-metadata            4.11.3 <--
importlib-resources           5.2.0  <--
inflection                    0.5.1
intervaltree                  3.1.0
ipykernel                     6.9.1
ipython                       7.31.1
ipython-genutils              0.2.0
isort                         5.9.3
jedi                          0.18.1
Jinja2                        3.0.3
jinja2-time                   0.2.0
joblib                        1.1.0
jsonschema                    4.4.0
jupyter-client                6.1.12  <--
jupyter-core                  4.10.0
jupyterlab-pygments           0.1.2
keras                         2.9.0
Keras-Applications            1.0.8
Keras-Preprocessing           1.1.2
keyring                       23.4.0
kiwisolver                    1.4.3
lazy-object-proxy             1.6.0
libclang                      14.0.1
Markdown                      3.3.7
MarkupSafe                    2.1.1
matplotlib                    3.5.2  <--
matplotlib-inline             0.1.2
mccabe                        0.6.1
mistune                       0.8.4
mkl-fft                       1.3.1
mkl-random                    1.2.2
mkl-service                   2.4.0
moviepy                       1.0.3  <--
multidict                     5.1.0
mypy-extensions               0.4.3
nbclient                      0.5.13
nbconvert                     6.4.4
nbformat                      5.3.0
nest-asyncio                  1.5.5
networkx                      2.6.3
numpy                         1.21.6
numpydoc                      1.4.0
oauthlib                      3.2.0
opencv-python                 4.6.0.66
opt-einsum                    3.3.0
packaging                     21.3
pandocfilters                 1.5.0
paramiko                      2.8.1
parso                         0.8.3
pathspec                      0.7.0
pexpect                       4.8.0
pickleshare                   0.7.5
Pillow                        9.2.0
pip                           22.1.2
pluggy                        1.0.0
poyo                          0.5.0
proglog                       0.1.10
prompt-toolkit                3.0.20
protobuf                      3.20.1
psutil                        5.9.0
ptyprocess                    0.7.0
pyasn1                        0.4.8
pyasn1-modules                0.2.8
pycodestyle                   2.7.0
pycparser                     2.21
pydocstyle                    6.1.1
pyflakes                      2.3.1
Pygments                      2.11.2
PyJWT                         2.4.0
pylint                        2.9.6
pyls-spyder                   0.4.0
PyNaCl                        1.4.0
pyOpenSSL                     22.0.0
pyparsing                     3.0.4
pyreadline                    2.1
pyrsistent                    0.18.0
PySocks                       1.7.1
python-dateutil               2.8.2
python-lsp-black              1.0.0
python-lsp-jsonrpc            1.0.0
python-lsp-server             1.2.4
python-slugify                5.0.2
pytz                          2022.1
PyWavelets                    1.3.0
pywin32                       302
pywin32-ctypes                0.2.0
PyYAML                        6.0
pyzmq                         23.2.0
QDarkStyle                    3.0.2
qstylizer                     0.1.10
QtAwesome                     1.0.3
qtconsole                     5.3.1
QtPy                          2.0.1
regex                         2022.3.15
requests                      2.28.1
requests-oauthlib             1.3.1
rope                          0.22.0
rsa                           4.8
Rtree                         0.9.7
scikit-image                  0.19.3 <--
scikit-learn                  0.22   <--
scipy                         1.7.3
setuptools                    61.2.0
sip                           4.19.13
six                           1.16.0
snowballstemmer               2.2.0
sortedcontainers              2.4.0
soupsieve                     2.3.1
Sphinx                        5.0.2
sphinxcontrib-applehelp       1.0.2
sphinxcontrib-devhelp         1.0.2
sphinxcontrib-htmlhelp        2.0.0
sphinxcontrib-jsmath          1.0.1
sphinxcontrib-qthelp          1.0.3
sphinxcontrib-serializinghtml 1.1.5
spyder                        5.1.5
spyder-kernels                2.1.3
tensorboard                   2.9.1
tensorboard-data-server       0.6.1
tensorboard-plugin-wit        1.8.1
tensorflow                    2.9.1 <--
tensorflow-estimator          2.9.0
tensorflow-io-gcs-filesystem  0.26.0
termcolor                     1.1.0
testpath                      0.6.0
text-unidecode                1.3
textdistance                  4.2.1
threadpoolctl                 3.1.0
three-merge                   0.1.1
tifffile                      2021.11.2
tinycss                       0.4
toml                          0.10.2
tornado                       6.1
tqdm                          4.64.0
traitlets                     5.1.1
typed-ast                     1.4.3
typing_extensions             4.1.1
ujson                         5.4.0
Unidecode                     1.2.0
urllib3                       1.26.9
watchdog                      2.1.6
wcwidth                       0.2.5
webencodings                  0.5.1
Werkzeug                      2.1.2
wheel                         0.37.1
win-inet-pton                 1.1.0
wincertstore                  0.2
wrapt                         1.12.1
yapf                          0.31.0
yarl                          1.6.3
zipp                          3.8.0
```
