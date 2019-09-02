<div class="github-widget" data-repo="faroit/awesome-python-scientific-audio"></div>
<script async src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js"></script><ins class="adsbygoogle" style="display:block" data-ad-client="ca-pub-6890694312814945" data-ad-slot="5473692530" data-ad-format="auto"  data-full-width-responsive="true"></ins><script>(adsbygoogle = window.adsbygoogle || []).push({});</script>
## Python for Scientific Audio [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)
[![Build Status](https://travis-ci.org/faroit/awesome-python-scientific-audio.svg?branch=master)](https://travis-ci.org/faroit/awesome-python-scientific-audio)

该存储库的目的是创建一个全面的策划列表，其中包含与音频/音乐应用中的科学研究相关的python软件/工具.




## Audio Related Packages

- Total number of packages: 72
-  Python版本兼容性：  ![69](http://progressed.io/bar/96?title=python%202) ![63](http://progressed.io/bar/86?title=python%203) （²表示只有python 2的包，³表示只有python 3的包;剩下的包支持python 2 + 3）.

#### Read-Write

* [audiolazy](https://github.com/danilobellini/audiolazy) [:octocat:](https://github.com/danilobellini/audiolazy) [:package:](https://pypi.python.org/pypi/audiolazy/) - 用于Python的表达式数字信号处理（DSP）包.
* [audioread](https://github.com/beetbox/audioread) [:octocat:](https://github.com/beetbox/audioread) [:package:](https://pypi.python.org/pypi/audioread/) - 跨库（GStreamer + Core Audio + MAD + FFmpeg）音频解码.
* [mutagen](https://mutagen.readthedocs.io/) [:octocat:](https://github.com/quodlibet/mutagen) [:package:](https://pypi.python.org/pypi/mutagen) - 读取和写入各种格式的各种音频元数据.
* [pyAV](https://mikeboers.github.io/PyAV/) [:octocat:](https://mikeboers.github.io/PyAV/) -  PyAV是FFmpeg或Libav的Pythonic绑定.
* [(Py)Soundfile](http://pysoundfile.readthedocs.io/) [:octocat:](https://github.com/bastibe/PySoundFile) [:package:](https://pypi.python.org/pypi/SoundFile) - 基于libsndfile，CFFI和NumPy的库.
* [pySox](https://github.com/rabitt/pysox) [:octocat:](https://github.com/rabitt/pysox) [:package:](https://pypi.python.org/pypi/pysox/) -  sox包装.
* [PySynth](http://mdoege.github.io/PySynth) [:octocat:](https://github.com/mdoege/PySynth) - 简单的midi-to-wav合成器.
* [stempeg](https://github.com/faroit/stempeg) [:octocat:](https://github.com/faroit/stempeg) [:package:](https://pypi.python.org/pypi/stempeg/) - 读/写STEMS多流音频.
* [tinytag](https://github.com/devsnd/tinytag) [:octocat:](https://github.com/devsnd/tinytag) [:package:](https://pypi.python.org/pypi/tinytag/) - 阅读MP3，OGG，FLAC和Wave文件的音乐元数据.
* [audiomate](https://github.com/ynop/audiomate)³ [:octocat:](https://github.com/ynop/audiomate) [:package:](https://pypi.python.org/pypi/audiomate/) - 加载不同类型的音频数据集.

#### Transformations - General DSP

* [acoustics](http://python-acoustics.github.io/python-acoustics/) [:octocat:](https://github.com/python-acoustics/python-acoustics/) [:package:](https://pypi.python.org/pypi/acoustics) - 为声学家提供有用的工具.
* [AudioTK](https://github.com/mbrucher/AudioTK) [:octocat:](https://github.com/mbrucher/AudioTK) -  DSP滤波器工具箱（大量滤波器）.
* [AudioTSM](https://audiotsm.readthedocs.io/) [:octocat:](https://github.com/Muges/audiotsm) [:package:](https://pypi.python.org/pypi/audiotsm/) - 实时音频时标修改程序.
* [Gammatone](https://github.com/detly/gammatone) [:octocat:](https://github.com/detly/gammatone) -  Gammatone滤波器组实现.
* [pyFFTW](http://pyfftw.github.io/pyFFTW/) [:octocat:](https://github.com/pyFFTW/pyFFTW) [:package:](https://pypi.python.org/pypi/pyFFTW/) - 用于FFTW的包装器（3）.
* [NSGT](https://grrrr.org/research/software/nsgt/) [:octocat:](https://github.com/grrrr/nsgt) [:package:](https://pypi.python.org/pypi/nsgt) - 非定常gabor变换，常数q.
* [MDCT](https://github.com/nils-werner/mdct) [:octocat:](https://github.com/nils-werner/mdct) [:package:](https://pypi.python.org/pypi/mdct) -  MDCT变换.
* [pydub](http://pydub.com) [:octocat:](https://github.com/jiaaro/pydub) [:package:](https://pypi.python.org/pypi/mdct) - 使用简单易用的高级界面处理音频.
* [pytftb](http://tftb.nongnu.org) [:octocat:](https://github.com/scikit-signal/pytftb) -  MATLAB时频工具箱的实现.
* [pyroomacoustics](https://github.com/LCAV/pyroomacoustics) [:octocat:](https://github.com/LCAV/pyroomacoustics) [:package:](https://pypi.python.org/pypi/pyroomacoustics) - 室内声学仿真（RIR发生器）
* [PyRubberband](https://github.com/bmcfee/pyrubberband) [:octocat:](https://github.com/bmcfee/pyrubberband) [:package:](https://pypi.python.org/pypi/pyrubberband/) - 包装纸 [rubberband](http://breakfastquay.com/rubberband/) 进行音高变换和时间拉伸.
* [PyWavelets](http://pywavelets.readthedocs.io) [:octocat:](https://github.com/PyWavelets/pywt) [:package:](https://pypi.python.org/pypi/PyWavelets) -  Python中的离散小波变换.
* [Resampy](http://resampy.readthedocs.io) [:octocat:](https://github.com/bmcfee/resampy) [:package:](https://pypi.python.org/pypi/resampy) - 采样率转换.
* [SFS-Python](http://sfstoolbox.org/) [:octocat:](https://github.com/sfstoolbox/sfs-python) [:package:](https://pypi.python.org/pypi/sfs/) - 声场合成工具箱.
* [STFT](http://stft.readthedocs.io) [:octocat:](https://github.com/nils-werner/stft) [:package:](https://pypi.python.org/pypi/stft) - 用于短时傅里叶变换的独立包.

#### Feature extraction

* [aubio](http://aubio.org/) [:octocat:](https://github.com/aubio/aubio) [:package:](https://pypi.python.org/pypi/aubio) - 特征提取器，用C语言编写，Python接口.
* [audiolazy](https://github.com/danilobellini/audiolazy) [:octocat:](https://github.com/danilobellini/audiolazy) [:package:](https://pypi.python.org/pypi/audiolazy/) - 实时音频处理库，通用.
* [essentia](http://essentia.upf.edu) [:octocat:](https://github.com/MTG/essentia) - 音乐相关的低级和高级特征提取器，基于C ++，包括Python绑定.
* [muda](https://muda.readthedocs.io/en/latest/) [:octocat:](https://github.com/bmcfee/muda) [:package:](https://pypi.python.org/pypi/muda) - 音乐数据增强.
* [python_speech_features](https://github.com/jameslyons/python_speech_features) [:octocat:](https://github.com/jameslyons/python_speech_features) [:package:](https://pypi.python.org/pypi/python_speech_features) -  ASR的常见语音功能.
* [pyYAAFE](https://github.com/Yaafe/Yaafe) [:octocat:](https://github.com/Yaafe/Yaafe) -  YAAFE功能提取器的Python绑定.
* [speechpy](https://github.com/astorfi/speechpy) [:octocat:](https://github.com/astorfi/speechpy) [:package:](https://pypi.python.org/pypi/speechpy) - 语音处理和识别库，目前主要是特征提取.

#### Speech Processing

* [aeneas](https://www.readbeyond.it/aeneas/) [:octocat:](https://github.com/readbeyond/aeneas/) [:package:](https://pypi.python.org/pypi/aeneas/) - 强制对准器，基于MFCC + DTW，35种以上语言.
* [Parselmouth](https://github.com/YannickJadoul/Parselmouth) [:octocat:](https://github.com/YannickJadoul/Parselmouth) [:package:](https://pypi.org/project/praat-parselmouth/) -  Python界面 [Praat](http://www.praat.org) 语音和语音分析，综合和操作软件.
* [pyAudioAnalysis](https://github.com/tyiannak/pyAudioAnalysis)² [:octocat:](https://github.com/tyiannak/pyAudioAnalysis) [:package:](https://pypi.python.org/pypi/pyAudioAnalysis/) - 特征提取，分类，Diarization.
* [py-webrtcvad](https://github.com/wiseman/py-webrtcvad) [:octocat:](https://github.com/wiseman/py-webrtcvad) [:package:](https://pypi.python.org/pypi/webrtcvad/) -  WebRTC语音活动检测器的接口.
* [PyWorldVocoder](https://github.com/JeremyCCHsu/Python-Wrapper-for-World-Vocoder) [:octocat:](https://github.com/JeremyCCHsu/Python-Wrapper-for-World-Vocoder) -  Morise世界声码器的包装.
* [Montreal Forced Aligner](https://montrealcorpustools.github.io/Montreal-Forced-Aligner/) [:octocat:](https://github.com/MontrealCorpusTools/Montreal-Forced-Aligner) - 强制对齐器，基于Kaldi（HMM），英语（其他人可以训练）.
* [SIDEKIT](http://lium.univ-lemans.fr/sidekit/)³ [:package:](https://pypi.python.org/pypi/SIDEKIT/) - 演讲者和语言识别.
* [SpeechRecognition](https://github.com/Uberi/speech_recognition) [:octocat:](https://github.com/Uberi/speech_recognition) [:package:](https://pypi.python.org/pypi/SpeechRecognition/) - 适用于多个ASR引擎和API的在线和离线包装.

#### Perceptial Models - Auditory Models

* [cochlea](https://github.com/mrkrd/cochlea)² [:octocat:](https://github.com/mrkrd/cochlea) [:package:](https://pypi.python.org/pypi/cochlea/) - 内耳模型.
* [Brian2](http://briansimulator.org/) [:octocat:](https://github.com/brian-team/brian2) [:package:](https://pypi.python.org/pypi/Brian2) - 尖峰神经网络模拟器，包括耳蜗模型.
* [Loudness](https://github.com/deeuu/loudness)³ [:octocat:](https://github.com/deeuu/loudness) - 感知响度，包括Zwicker，Moore / Glasberg模型.
* [Sound Field Synthesis Toolbox](http://sfstoolbox.org/) [:octocat:](https://github.com/sfstoolbox/sfs-python) [:package:](https://pypi.python.org/pypi/sfs/) - 声场合成工具箱.

#### Source Separation

* [beta_ntf](https://code.google.com/archive/p/beta-ntf/)² [:octocat:](https://github.com/nils-werner/beta_ntf) - 使用PARAFAC的非负张量因子分解.
* [commonfate](https://github.com/aliutkus/commonfate) [：octocat：]（） [:package:](https://pypi.python.org/pypi/commonfate) - 共同的命运模型和变换.
* [NUSSL](https://interactiveaudiolab.github.io/nussl/)² [:octocat:](https://github.com/interactiveaudiolab/nussl) [:package:](https://pypi.python.org/pypi/nussl) - 各种源分离算法+框架.
* [NTFLib](https://github.com/stitchfix/NTFLib) [:octocat:](https://github.com/stitchfix/NTFLib) - 稀疏的Beta-发散张量分解.
* [NIMFA](http://nimfa.biolab.si) [:octocat:](https://github.com/marinkaz/nimfa) [:package:](https://pypi.python.org/pypi/nimfa) - 几种NMF口味.
* [pyFASST](https://github.com/wslihgt/pyfasst)² [:octocat:](https://github.com/wslihgt/pyfasst) [:package:](https://pypi.python.org/pypi/pyFASST) - 用于灵活音频源分离工具箱的包装器.

#### Music Information Retrieval

* [Catchy](https://github.com/jvbalen/catchy) [:octocat:](https://github.com/jvbalen/catchy) - 用于计算钩子发现的语料库分析工具.
* [dejavu](http://willdrevo.com/fingerprinting-and-audio-recognition-with-python/)² [:octocat:](https://github.com/worldveil/dejavu) [:package:](https://pypi.python.org/pypi/PyDejavu) - 音频指纹识别和识别.
* [Madmom](https://madmom.readthedocs.io/en/latest/) [:octocat:](https://github.com/CPJKU/madmom) [:package:](https://pypi.python.org/pypi/madmom) -  MIR包，重点关注节拍检测，起始检测和和弦识别.
* [mir_eval](http://craffel.github.io/mir_eval/) [:octocat:](https://github.com/craffel/mir_eval) [:package:](https://pypi.python.org/pypi/mir_eval)   - 各种MIR任务的共同分数.  还包括bss_eval实现.
* [msaf](http://pythonhosted.org/msaf/) [:octocat:](https://github.com/urinieto/msaf) [:package:](https://pypi.python.org/pypi/msaf) - 音乐结构分析框架.
* [librosa](http://librosa.github.io/librosa/) [:octocat:](https://github.com/librosa/librosa) [:package:](https://pypi.python.org/pypi/librosa) - 一般音频和音乐分析.
* [rp_extract](https://github.com/tuwien-musicir/rp_extract)² [:octocat:](https://github.com/tuwien-musicir/rp_extract) -  Rhythm Pattern音乐特色提取器.

#### Deep Learning

* [Kapre](https://github.com/keunwoochoi/kapre) [:octocat:](https://github.com/keunwoochoi/kapre) [:package:](https://pypi.python.org/pypi/kapre) - 响亮的音频预处理器
* [TorchAudio](https://github.com/pytorch/audio) [:octocat:](https://github.com/pytorch/audio) -  PyTorch音频加载器

#### Symbolic Music - MIDI - Musicology

* [Music21](http://web.mit.edu/music21/) [:octocat:](https://github.com/cuthbertLab/music21) [:package:](https://pypi.python.org/pypi/music21) - 计算机辅助音乐学工具包.
* [Mido](https://mido.readthedocs.io/en/latest/) [:octocat:](https://github.com/olemb/mido) [:package:](https://pypi.python.org/pypi/mido) - 实时MIDI包装.
* [mingus](http://bspaans.github.io/python-mingus/)² [:octocat:](https://github.com/bspaans/python-mingus) [:package:](https://pypi.python.org/pypi/mingus/) - 具有MIDI文件和播放支持的高级音乐理论和符号包.
* [Pretty-MIDI](http://craffel.github.io/pretty-midi/) [:octocat:](https://github.com/craffel/pretty-midi) [:package:](https://pypi.python.org/pypi/pretty-midi) - 实用功能，以美观/直观的方式处理MIDI数据.

#### Realtime applications

* [PYO](http://ajaxsoundstudio.com/software/pyo/) [:octocat:](https://github.com/belangeo/pyo) - 实时音频dsp引擎.
* [python-sounddevice](https://github.com/spatialaudio/python-sounddevice) [:octocat:](http://python-sounddevice.readthedocs.io) [:package:](https://pypi.python.org/pypi/sounddevice) -  PortAudio包装器，提供NumPy的实时音频I / O.

#### Web Audio

* [TimeSide](https://github.com/Parisson/TimeSide)² [:octocat:](https://github.com/Parisson/TimeSide) - 高级音频分析，成像，转码，流媒体和标签.

#### Audio related APIs and Datasets

* [beets](http://beets.io/) [:octocat:](https://github.com/beetbox/beets) [:package:](https://pypi.python.org/pypi/beets) - 音乐图书馆经理和 [MusicBrainz](https://musicbrainz.org/) 标签.
* [dsdtools](http://dsdtools.readthedocs.io) [:octocat:](https://github.com/faroit/dsdtools) [:package:](https://pypi.python.org/pypi/dsdtools) - 解析并处理 [demixing secrets dataset](http://sisec17.audiolabs-erlangen.de/#/dataset).
* [medleydb](http://medleydb.readthedocs.io) [:octocat:](https://github.com/marl/medleydb) - 解析 [medleydb](http://medleydb.weebly.com/) 音频+注释.
* [Soundcloud API](https://github.com/soundcloud/soundcloud-python) [:octocat:](https://github.com/soundcloud/soundcloud-python) [:package:](https://pypi.python.org/pypi/soundcloud) - 包装纸 [Soundcloud API](https://developers.soundcloud.com/).
* [Youtube-Downloader](http://rg3.github.io/youtube-dl/) [:octocat:](https://github.com/rg3/youtube-dl) [:package:](https://pypi.python.org/pypi/youtube_dl) - 下载YouTube视频（和音频）.

#### Wrappers for Audio Plugins

* [VamPy Host](https://code.soundsoftware.ac.uk/projects/vampy-host) [:package:](https://pypi.python.org/pypi/vamp) - 接口编译的vamp插件.

## Tutorials

* [Whirlwind Tour Of Python](https://jakevdp.github.io/WhirlwindTourOfPython/) [：octocat：]（https://github.com/jakevdp/WhirlwindTourOfPython
） - 针对研究人员和开发人员快速介绍Python要点.
* [Introduction to Numpy and Scipy](http://www.scipy-lectures.org/index.html) [:octocat:](https://github.com/scipy-lectures/scipy-lecture-notes) - 强烈推荐的教程，涵盖科学Python生态系统的大部分内容.
* [Numpy for MATLAB® Users](https://docs.scipy.org/doc/numpy/user/numpy-for-matlab-users.html) - 切换器的等效python函数的简短概述.
* [MIR Notebooks](http://musicinformationretrieval.com/) [:octocat:](https://github.com/stevetjoa/stanford-mir) - 收集用于音乐信息检索（MIR）的教学iPython笔记本.
* [Selected Topics in Audio Signal Processing](https://github.com/faroit/awesome-python-scientific-audio/blob/master/ https://github.com/spatialaudio/selected-topics-in-audio-signal-processing-exercises) - 作为iPython笔记本练习.

## Books

* [Python Data Science Handbook](https://github.com/jakevdp/PythonDataScienceHandbook) -  Jake Vanderplas，优秀书籍和随附的教程笔记本.
* [Fundamentals of Music Processing](https://www.audiolabs-erlangen.de/fau/professor/mueller/bookFMP) - MeinardMüller，附带Python练习.

## Scientific Papers

* [Python for audio signal processing](http://eprints.maynoothuniversity.ie/4115/1/40.pdf) -  John C. Glover，Victor Lazzarini和Joseph Timoney，2011年Linux音频会议.
* [librosa: Audio and Music Signal Analysis in Python](http://conference.scipy.org/proceedings/scipy2015/pdfs/brian_mcfee.pdf), [Video](https://www.youtube.com/watch?v=MhOdbtPhbLU) -  Brian McFee，Colin Raffel，Dawen Liang，Daniel PW Ellis，Matt McVicar，Eric Battenberg，Oriol Nieto，Scipy 2015.

## Other Resources

* [Coursera Course](https://www.coursera.org/learn/audio-signal-processing) - 音频信号处理，基于Python的课程，来自巴塞罗那和斯坦福大学的UPF.
* [Digital Signal Processing Course](http://dsp-nbsphinx.readthedocs.io/en/nbsphinx-experiment/index.html) - 拥有许多Python示例的硕士课程材料（罗斯托克大学）.
* [Slack Channel](https://mircommunity.slack.com) - 音乐信息检索社区.

## Related lists

已经有了 [PythonInMusic](https://wiki.python.org/moin/PythonInMusic) 但它不是最新的，包含太多特别感兴趣的包装，这些包装大多与科学应用无关. [Awesome-Python](https://github.com/vinta/awesome-python)  是python包的大型精选列表.  但是，音频部分非常小.

## Contributing

 欢迎您的贡献！  请看看 [contribution guidelines](https://github.com/faroit/awesome-python-scientific-audio/blob/master/CONTRIBUTING.md) 第一.

如果我不确定这些库是否真棒，我会保留一些拉请求，你可以通过添加它们来投票.

## License

[![License: CC BY 4.0](https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by/4.0/)
