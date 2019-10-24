<div class="github-widget" data-repo="faroit/awesome-python-scientific-audio"></div>
<script async src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js"></script><ins class="adsbygoogle" style="display:block" data-ad-client="ca-pub-6890694312814945" data-ad-slot="5473692530" data-ad-format="auto"  data-full-width-responsive="true"></ins><script>(adsbygoogle = window.adsbygoogle || []).push({});</script>
## Python for Scientific Audio [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)
[![Build Status](https://travis-ci.org/faroit/awesome-python-scientific-audio.svg?branch=master)](https://travis-ci.org/faroit/awesome-python-scientific-audio)

该存储库的目的是创建与Python相关的，用于音频/音乐应用科学研究的python软件/工具的全面清单.




## Audio Related Packages

-包裹总数：79
-Python版本兼容性：²表示仅python 2的软件包，其余软件包支持python 3）.

#### Read-Write

* [audiolazy](https://github.com/danilobellini/audiolazy) [:octocat:](https://github.com/danilobellini/audiolazy) [:package:](https://pypi.python.org/pypi/audiolazy/) -用于Python的富有表现力的数字信号处理（DSP）软件包.
* [audioread](https://github.com/beetbox/audioread) [:octocat:](https://github.com/beetbox/audioread) [:package:](https://pypi.python.org/pypi/audioread/) -跨库（GStreamer +核心音频+ MAD + FFmpeg）音频解码.
* [mutagen](https://mutagen.readthedocs.io/) [:octocat:](https://github.com/quodlibet/mutagen) [:package:](https://pypi.python.org/pypi/mutagen) -读取和写入各种格式的所有音频元数据.
* [pyAV](https://mikeboers.github.io/PyAV/) [:octocat:](https://mikeboers.github.io/PyAV/) -PyAV是FFmpeg或Libav的Python绑定.
* [(Py)Soundfile](http://pysoundfile.readthedocs.io/) [:octocat:](https://github.com/bastibe/PySoundFile) [:package:](https://pypi.python.org/pypi/SoundFile) -基于libsndfile，CFFI和NumPy的库.
* [pySox](https://github.com/rabitt/pysox) [:octocat:](https://github.com/rabitt/pysox) [:package:](https://pypi.python.org/pypi/pysox/) -袜子包装.
* [PySynth](http://mdoege.github.io/PySynth) [:octocat:](https://github.com/mdoege/PySynth) -简单的波形合成器.
* [stempeg](https://github.com/faroit/stempeg) [:octocat:](https://github.com/faroit/stempeg) [:package:](https://pypi.python.org/pypi/stempeg/) -读/写STEMS多流音频.
* [tinytag](https://github.com/devsnd/tinytag) [:octocat:](https://github.com/devsnd/tinytag) [:package:](https://pypi.python.org/pypi/tinytag/) -读取MP3，OGG，FLAC和Wave文件的音乐元数据.
* [audiomate](https://github.com/ynop/audiomate) [:octocat:](https://github.com/ynop/audiomate) [:package:](https://pypi.python.org/pypi/audiomate/) -加载不同类型的音频数据集.

#### Transformations - General DSP

* [acoustics](http://python-acoustics.github.io/python-acoustics/) [:octocat:](https://github.com/python-acoustics/python-acoustics/) [:package:](https://pypi.python.org/pypi/acoustics) -声学师的有用工具.
* [AudioTK](https://github.com/mbrucher/AudioTK) [:octocat:](https://github.com/mbrucher/AudioTK) -DSP过滤器工具箱（许多过滤器）.
* [AudioTSM](https://audiotsm.readthedocs.io/) [:octocat:](https://github.com/Muges/audiotsm) [:package:](https://pypi.python.org/pypi/audiotsm/) -实时音频时标修改程序.
* [Gammatone](https://github.com/detly/gammatone) [:octocat:](https://github.com/detly/gammatone) -Gammatone滤波器组的实现.
* [pyFFTW](http://pyfftw.github.io/pyFFTW/) [:octocat:](https://github.com/pyFFTW/pyFFTW) [:package:](https://pypi.python.org/pypi/pyFFTW/) -FFTW（3）的包装器.
* [NSGT](https://grrrr.org/research/software/nsgt/) [:octocat:](https://github.com/grrrr/nsgt) [:package:](https://pypi.python.org/pypi/nsgt) -非平稳gabor变换，常数q.
* [MDCT](https://github.com/nils-werner/mdct) [:octocat:](https://github.com/nils-werner/mdct) [:package:](https://pypi.python.org/pypi/mdct) -MDCT转换.
* [pydub](http://pydub.com) [:octocat:](https://github.com/jiaaro/pydub) [:package:](https://pypi.python.org/pypi/mdct) -通过简单易用的高级界面处理音频.
* [pytftb](http://tftb.nongnu.org) [:octocat:](https://github.com/scikit-signal/pytftb) -MATLAB时频工具箱的实现.
* [pyroomacoustics](https://github.com/LCAV/pyroomacoustics) [:octocat:](https://github.com/LCAV/pyroomacoustics) [:package:](https://pypi.python.org/pypi/pyroomacoustics) -室内声学模拟（RIR发生器）
* [PyRubberband](https://github.com/bmcfee/pyrubberband) [:octocat:](https://github.com/bmcfee/pyrubberband) [:package:](https://pypi.python.org/pypi/pyrubberband/) -包装 [rubberband](http://breakfastquay.com/rubberband/) 进行音调转换和时间拉伸.
* [PyWavelets](http://pywavelets.readthedocs.io) [:octocat:](https://github.com/PyWavelets/pywt) [:package:](https://pypi.python.org/pypi/PyWavelets) -Python中的离散小波变换.
* [Resampy](http://resampy.readthedocs.io) [:octocat:](https://github.com/bmcfee/resampy) [:package:](https://pypi.python.org/pypi/resampy) - Sample rate conversion.
* [SFS-Python](http://www.sfstoolbox.org) [:octocat:](https://github.com/sfstoolbox/sfs-python) [:package:](https://pypi.python.org/pypi/sfs/) -声场综合工具箱.
* [STFT](http://stft.readthedocs.io) [:octocat:](https://github.com/nils-werner/stft) [:package:](https://pypi.python.org/pypi/stft) -用于短时傅立叶变换的独立程序包.

#### Feature extraction

* [aubio](http://aubio.org/) [:octocat:](https://github.com/aubio/aubio) [:package:](https://pypi.python.org/pypi/aubio) -特征提取器，用C，Python接口编写.
* [audiolazy](https://github.com/danilobellini/audiolazy) [:octocat:](https://github.com/danilobellini/audiolazy) [:package:](https://pypi.python.org/pypi/audiolazy/) -实时音频处理库，通用.
* [essentia](http://essentia.upf.edu) [:octocat:](https://github.com/MTG/essentia) -与音乐相关的低级和高级功能提取器，基于C ++，包括Python绑定.
* [muda](https://muda.readthedocs.io/en/latest/) [:octocat:](https://github.com/bmcfee/muda) [:package:](https://pypi.python.org/pypi/muda) -音乐数据增强.
* [python_speech_features](https://github.com/jameslyons/python_speech_features) [:octocat:](https://github.com/jameslyons/python_speech_features) [:package:](https://pypi.python.org/pypi/python_speech_features) -ASR的通用语音功能.
* [pyYAAFE](https://github.com/Yaafe/Yaafe) [:octocat:](https://github.com/Yaafe/Yaafe) -YAAFE功能提取器的Python绑定.
* [speechpy](https://github.com/astorfi/speechpy) [:octocat:](https://github.com/astorfi/speechpy) [:package:](https://pypi.python.org/pypi/speechpy) -语音处理和识别库，目前主要是特征提取.

#### Speech Processing

* [aeneas](https://www.readbeyond.it/aeneas/) [:octocat:](https://github.com/readbeyond/aeneas/) [:package:](https://pypi.python.org/pypi/aeneas/) -基于MFCC + DTW，35种以上语言的强制对齐器.
* [deepspeech](https://github.com/mozilla/DeepSpeech) [:octocat:](https://github.com/mozilla/DeepSpeech) [:package:](https://pypi.org/project/deepspeech/) -预训练的自动语音识别.
* [gentle](https://lowerquality.com/gentle/) [:octocat:](https://github.com/lowerquality/gentle) -基于Kaldi的强制对准器.
* [Parselmouth](https://github.com/YannickJadoul/Parselmouth) [:octocat:](https://github.com/YannickJadoul/Parselmouth) [:package:](https://pypi.org/project/praat-parselmouth/) -Python接口 [Praat](http://www.praat.org) 语音和语音分析，合成和操纵软件.
* [persephone](https://persephone.readthedocs.io/en/latest/) [:octocat:](https://github.com/persephone-tools/persephone) [:package:](https://pypi.org/project/persephone/) -自动音素转录工具.
* [pyAudioAnalysis](https://github.com/tyiannak/pyAudioAnalysis)² [:octocat:](https://github.com/tyiannak/pyAudioAnalysis) [:package:](https://pypi.python.org/pypi/pyAudioAnalysis/) -特征提取，分类，数字化.
* [py-webrtcvad](https://github.com/wiseman/py-webrtcvad) [:octocat:](https://github.com/wiseman/py-webrtcvad) [:package:](https://pypi.python.org/pypi/webrtcvad/) -与WebRTC语音活动检测器的接口.
* [pypesq](https://github.com/vBaiCai/python-pesq) [:octocat:](https://github.com/vBaiCai/python-pesq) -用于PESQ分数计算的包装器.
* [pystoi](https://github.com/mpariente/pystoi) [:octocat:](https://github.com/mpariente/pystoi) [:package:](https://pypi.org/project/pystoi) -短期目标可理解性度量（STOI）.
* [PyWorldVocoder](https://github.com/JeremyCCHsu/Python-Wrapper-for-World-Vocoder) [:octocat:](https://github.com/JeremyCCHsu/Python-Wrapper-for-World-Vocoder) -Morise的World Vocoder包装.
* [Montreal Forced Aligner](https://montrealcorpustools.github.io/Montreal-Forced-Aligner/) [:octocat:](https://github.com/MontrealCorpusTools/Montreal-Forced-Aligner) -基于Kaldi（HMM），英语的强制对准器（可以训练其他对准器）.
* [SIDEKIT](http://lium.univ-lemans.fr/sidekit/) [:package:](https://pypi.python.org/pypi/SIDEKIT/) -说话者和语言识别.
* [SpeechRecognition](https://github.com/Uberi/speech_recognition) [:octocat:](https://github.com/Uberi/speech_recognition) [:package:](https://pypi.python.org/pypi/SpeechRecognition/) -用于多个在线和离线ASR引擎和API的包装器.

#### Environmental Sounds

* [sed_eval](http://tut-arg.github.io/sed_eval) [:octocat:](https://github.com/TUT-ARG/sed_eval) [:package:](https://pypi.org/project/sed_eval/) -声音事件检测的评估工具箱

#### Perceptial Models - Auditory Models

* [cochlea](https://github.com/mrkrd/cochlea)² [:octocat:](https://github.com/mrkrd/cochlea) [:package:](https://pypi.python.org/pypi/cochlea/) -内耳模型.
* [Brian2](http://briansimulator.org/) [:octocat:](https://github.com/brian-team/brian2) [:package:](https://pypi.python.org/pypi/Brian2) -刺神经网络模拟器，包括耳蜗模型.
* [Loudness](https://github.com/deeuu/loudness) [:octocat:](https://github.com/deeuu/loudness) -感知的响度，包括Zwicker，摩尔/格拉斯伯格模型.
* [pyloudnorm](https://www.christiansteinmetz.com/projects-blog/pyloudnorm) [:octocat:](https://github.com/csteinmetz1/pyloudnorm) -音频响度计和归一化，实现ITU-R BS.1770-4.
* [Sound Field Synthesis Toolbox](http://www.sfstoolbox.org) [:octocat:](https://github.com/sfstoolbox/sfs-python) [:package:](https://pypi.python.org/pypi/sfs/) -声场综合工具箱.

#### Source Separation

* [beta_ntf](https://code.google.com/archive/p/beta-ntf/)² [:octocat:](https://github.com/nils-werner/beta_ntf) -使用PARAFAC的非负张量分解.
* [commonfate](https://github.com/aliutkus/commonfate) [：octocat：]（） [:package:](https://pypi.python.org/pypi/commonfate) -共同的命运模型和转变.
* [NUSSL](https://interactiveaudiolab.github.io/nussl/)² [:octocat:](https://github.com/interactiveaudiolab/nussl) [:package:](https://pypi.python.org/pypi/nussl) -各种源分离算法+框架.
* [NTFLib](https://github.com/stitchfix/NTFLib) [:octocat:](https://github.com/stitchfix/NTFLib) -稀疏的Beta散度张量分解.
* [NIMFA](http://nimfa.biolab.si) [:octocat:](https://github.com/marinkaz/nimfa) [:package:](https://pypi.python.org/pypi/nimfa) -几种NMF口味.
* [pyFASST](https://github.com/wslihgt/pyfasst)² [:octocat:](https://github.com/wslihgt/pyfasst) [:package:](https://pypi.python.org/pypi/pyFASST) -灵活的音频源分离工具箱的包装器.

#### Music Information Retrieval

* [Catchy](https://github.com/jvbalen/catchy) [:octocat:](https://github.com/jvbalen/catchy) -用于计算挂钩的语料库分析工具.
* [dejavu](http://willdrevo.com/fingerprinting-and-audio-recognition-with-python/)² [:octocat:](https://github.com/worldveil/dejavu) [:package:](https://pypi.python.org/pypi/PyDejavu) -音频指纹识别.
* [Madmom](https://madmom.readthedocs.io/en/latest/) [:octocat:](https://github.com/CPJKU/madmom) [:package:](https://pypi.python.org/pypi/madmom) -MIR软件包非常注重节拍检测，起音检测和和弦识别.
* [mir_eval](http://craffel.github.io/mir_eval/) [:octocat:](https://github.com/craffel/mir_eval) [:package:](https://pypi.python.org/pypi/mir_eval)  -各种MIR任务的共同分数.  还包括bss_eval实现.
* [msaf](http://pythonhosted.org/msaf/) [:octocat:](https://github.com/urinieto/msaf) [:package:](https://pypi.python.org/pypi/msaf) -音乐结构分析框架.
* [librosa](http://librosa.github.io/librosa/) [:octocat:](https://github.com/librosa/librosa) [:package:](https://pypi.python.org/pypi/librosa) -常规音频和音乐分析.
* [rp_extract](https://github.com/tuwien-musicir/rp_extract)² [:octocat:](https://github.com/tuwien-musicir/rp_extract) -节奏模式音乐特征提取器.

#### Deep Learning

* [Kapre](https://github.com/keunwoochoi/kapre) [:octocat:](https://github.com/keunwoochoi/kapre) [:package:](https://pypi.python.org/pypi/kapre) -大声音频预处理器
* [TorchAudio](https://github.com/pytorch/audio) [:octocat:](https://github.com/pytorch/audio) -PyTorch音频加载器

#### Symbolic Music - MIDI - Musicology

* [Music21](http://web.mit.edu/music21/) [:octocat:](https://github.com/cuthbertLab/music21) [:package:](https://pypi.python.org/pypi/music21) -计算机辅助音乐学工具包.
* [Mido](https://mido.readthedocs.io/en/latest/) [:octocat:](https://github.com/olemb/mido) [:package:](https://pypi.python.org/pypi/mido) -实时MIDI包装器.
* [mingus](http://bspaans.github.io/python-mingus/)² [:octocat:](https://github.com/bspaans/python-mingus) [:package:](https://pypi.python.org/pypi/mingus/) -带有MIDI文件和播放支持的高级音乐理论和注释包.
* [Pretty-MIDI](http://craffel.github.io/pretty-midi/) [:octocat:](https://github.com/craffel/pretty-midi) [:package:](https://pypi.python.org/pypi/pretty-midi) -以良好/直观的方式处理MIDI数据的实用程序功能.

#### Realtime applications

* [PYO](http://ajaxsoundstudio.com/software/pyo/) [:octocat:](https://github.com/belangeo/pyo) -实时音频dsp引擎.
* [python-sounddevice](https://github.com/spatialaudio/python-sounddevice) [:octocat:](http://python-sounddevice.readthedocs.io) [:package:](https://pypi.python.org/pypi/sounddevice) -PortAudio包装器通过NumPy提供实时音频I / O.

#### Web Audio

* [TimeSide](https://github.com/Parisson/TimeSide)² [:octocat:](https://github.com/Parisson/TimeSide) -高级音频分析，成像，代码转换，流传输和标记.

#### Audio related APIs and Datasets

* [beets](http://beets.io/) [:octocat:](https://github.com/beetbox/beets) [:package:](https://pypi.python.org/pypi/beets) -音乐图书馆经理和 [MusicBrainz](https://musicbrainz.org/) 标签.
* [dsdtools](http://dsdtools.readthedocs.io) [:octocat:](https://github.com/faroit/dsdtools) [:package:](https://pypi.python.org/pypi/dsdtools) -解析并处理 [demixing secrets dataset](http://sisec17.audiolabs-erlangen.de/#/dataset).
* [medleydb](http://medleydb.readthedocs.io) [:octocat:](https://github.com/marl/medleydb) -解析 [medleydb](http://medleydb.weebly.com/) 音频和注释.
* [Soundcloud API](https://github.com/soundcloud/soundcloud-python) [:octocat:](https://github.com/soundcloud/soundcloud-python) [:package:](https://pypi.python.org/pypi/soundcloud) -包装 [Soundcloud API](https://developers.soundcloud.com/).
* [Youtube-Downloader](http://rg3.github.io/youtube-dl/) [:octocat:](https://github.com/rg3/youtube-dl) [:package:](https://pypi.python.org/pypi/youtube_dl) -下载youtube视频（和音频）.

#### Wrappers for Audio Plugins

* [VamPy Host](https://code.soundsoftware.ac.uk/projects/vampy-host) [:package:](https://pypi.python.org/pypi/vamp) -接口编译的鞋面插件.

## Tutorials

* [Whirlwind Tour Of Python](https://jakevdp.github.io/WhirlwindTourOfPython/) [：octocat：]（https://github.com/jakevdp/WhirlwindTourOfPython
）-针对研究人员和开发人员的Python基本要素的快速介绍.
* [Introduction to Numpy and Scipy](http://www.scipy-lectures.org/index.html) [:octocat:](https://github.com/scipy-lectures/scipy-lecture-notes) -高度推荐的教程，涵盖了科学的Python生态系统的大部分内容.
* [Numpy for MATLAB® Users](https://docs.scipy.org/doc/numpy/user/numpy-for-matlab-users.html) -等效的python功能的简短概述.
* [MIR Notebooks](http://musicinformationretrieval.com/) [:octocat:](https://github.com/stevetjoa/stanford-mir) -收集用于音乐信息检索（MIR）的教学iPython笔记本.
* [Selected Topics in Audio Signal Processing](https://github.com/faroit/awesome-python-scientific-audio/blob/master/ https://github.com/spatialaudio/selected-topics-in-audio-signal-processing-exercises) -作为iPython笔记本进行练习.

## Books

* [Python Data Science Handbook](https://github.com/jakevdp/PythonDataScienceHandbook) -杰克·范德普拉斯（Jake Vanderplas），《名著》和随附的教程笔记本.
* [Fundamentals of Music Processing](https://www.audiolabs-erlangen.de/fau/professor/mueller/bookFMP) -MeinardMüller，随附Python练习.

## Scientific Papers

* [Python for audio signal processing](http://eprints.maynoothuniversity.ie/4115/1/40.pdf) -John C.Glover，Victor Lazzarini和Joseph Timoney，2011年Linux音频会议.
* [librosa: Audio and Music Signal Analysis in Python](http://conference.scipy.org/proceedings/scipy2015/pdfs/brian_mcfee.pdf), [Video](https://www.youtube.com/watch?v=MhOdbtPhbLU) -Brian McFee，Colin Raffel，Dawen Liang，Daniel PW Ellis，Matt McVicar，Eric Battenberg，Oriol Nieto，Scipy 2015.

## Other Resources

* [Coursera Course](https://www.coursera.org/learn/audio-signal-processing) -音频信号处理，巴塞罗那和斯坦福大学UPF的基于Python的课程.
* [Digital Signal Processing Course](http://dsp-nbsphinx.readthedocs.io/en/nbsphinx-experiment/index.html) -具有许多Python示例的硕士学位课程资料（罗斯托克大学）.
* [Slack Channel](https://mircommunity.slack.com) -音乐信息检索社区.

## Related lists

已经有 [PythonInMusic](https://wiki.python.org/moin/PythonInMusic) 但是它不是最新的，并且包含了很多特别感兴趣的软件包，这些软件包大多数与科学应用无关. [Awesome-Python](https://github.com/vinta/awesome-python)  是大型精选的python软件包列表.  但是，音频部分很小.

## Contributing

 永远欢迎您的贡献！  请看看 [contribution guidelines](https://github.com/faroit/awesome-python-scientific-audio/blob/master/CONTRIBUTING.md) 第一.

如果不确定这些库是否很棒，我将打开一些拉取请求，您可以通过添加它们来投票支持它们.

## License

[![License: CC BY 4.0](https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by/4.0/)
