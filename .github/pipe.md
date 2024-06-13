## Car

* `智驾模型和应用`
  * 上海人工智能实验室CVPR'2023 best paper，UniAD：<https://github.com/OpenDriveLab/UniAD>
  * Transpose Convolutions and Autoencoders: <https://www.cs.toronto.edu/~lczhang/321/lec/autoencoder_notes.html>
  * grid sample线性插值：<https://zhuanlan.zhihu.com/p/112030273>
  * HDMapNet
    * HDMap在智驾中承担的角色：<https://auto.jgvogel.cn/c1302027.shtml>
    * HDMap建图技术总结：<https://zhuanlan.zhihu.com/p/600087910>
    * nuScenses示例图：<https://www.nuscenes.org/nuscenes#data-collection>
    * 相机内参：<https://www.cse.psu.edu/~rtc12/CSE486/lecture12.pdf>
  * BEVPoolV2: <https://arxiv.org/pdf/2211.17111> & <https://github.com/HuangJunJie2017/BEVDet/tree/dev2.0>
  * 旋转加平移（RT+P）转换成矩阵乘运算：<https://blog.51cto.com/u_15060515/3941933> & <https://github.com/zach0zhang/OpenGL_Learning/blob/master/Translation_Transformation/OpenGL%E5%AD%A6%E4%B9%A0%E4%B9%8B%E8%B7%AF6----%E5%B9%B3%E7%A7%BB%EF%BC%8C%E6%97%8B%E8%BD%AC%E5%92%8C%E7%BC%A9%E6%94%BE%E5%8F%98%E6%8D%A2.md>
* `车载芯片`
  * 常规神经网络算力需求：<https://blog.csdn.net/weixin_36474809/article/details/85675504>
  * 英伟达自动驾驶芯片演进历史：<https://en.wikipedia.org/wiki/Nvidia_Drive>
  * Tesla自动驾驶硬件进化史：<https://zhuanlan.zhihu.com/p/369300487>
  * Chris Lattner作为特斯拉自动驾驶软件的技术VP，经历了特斯拉第一代到第二代的过渡时期：<https://nondot.org/sabre/Resume.html#Tesla>
  * Tesla FSD 3.0芯片细节：<https://fuse.wikichip.org/news/2707/inside-teslas-neural-processor-in-the-fsd-chip/>
  * Tesla FSD 4.0: <https://after1989.com/teslas-latest-advancement-hardware-4-0/>
  * wikichip中的自动驾驶芯片：<https://en.wikichip.org/wiki/autonomous_driving_chip>
  * Dataflow架构特点：<https://1nfinite.ai/t/dataflow/97>
  * 车载智能计算芯片白皮书：<https://www.armchina.com/webarm/arm/material/download/profile/resource/2023/07/10/10f8e872-6da8-4c90-9e26-ddeb1084c415.pdf>
  * NVIDIA Hopper架构：<https://developer.nvidia.com/blog/nvidia-hopper-architecture-in-depth/>
  * NVIDIA SM cuda-cores list: <https://www.twisted-meadows.com/nvidia-gpu-architecture/>
* `车载OS`
  * 车载智能OS开源原型参考，FastDDS：<https://github.com/eProsima/Fast-DDS> & <https://zhuanlan.zhihu.com/p/488457744>
  * 科普系列
    * 车载软件与国产现状：<https://www.jishulink.com/post/1879680>
    * 车载OS三域(安全车载、座舱、智驾)现状(部分信息过时)：<https://zhuanlan.zhihu.com/p/672232647>
    * 2023整车操作系统发展趋势研究报告: <https://www.eet-china.com/mp/a250201.html>
* `编译和工具链`
  * llvm-project国内镜像仓库：<https://gitee.com/mirrors/LLVM>
  * onnx模型参数可视化在线工具：<https://netron.app/>
  * python table print库，prettytable: <https://pypi.org/project/prettytable/>
  * Book, Programming with 64-Bit ARM Assembly Language, <https://surma.dev/postits/arm64/>
  * 可重构计算，CGRA相关论文：<https://blog.sciencenet.cn/blog-3406013-1218187.html>
  * 斯坦福CGRA系列工作：<https://aha.stanford.edu/publications>
  * CGRA工具链：<https://www.tkojima.me/slides/2022/cgra4hpc2022_slide_kojima.pdf>
  * 百度昆仑芯架构科普：<https://zhuanlan.zhihu.com/p/646793342>
  * MESI和MOESI cache一致性协议：<https://east1203.github.io/2022/03/19/IC/Cache/MESI%E5%92%8CMOESI%20Cache%E4%B8%80%E8%87%B4%E6%80%A7%E5%8D%8F%E8%AE%AE/>
  * 内存一致性：<https://gfxcourses.stanford.edu/cs149/winter19content/lectures/09_consistency/09_consistency_slides.pdf>
  * virtqueue转盘模式：<https://nxw.name/2023/virtqueue>
  * ClangIR设计的动机和示例：<https://github.com/llvm/clangir> & <http://brunocardoso.cc/resources/2023-LLVMDevMtgClangIR.pdf> & <https://zhuanlan.zhihu.com/p/686260593>
  * openai triton基于MLIR重构记录：<https://superjomn.github.io/posts/triton-mlir-publish/#tritonir-%E7%9A%84%E4%BC%98%E5%8C%96>
  * Clang源源变换示例：<https://eli.thegreenplace.net/2014/05/01/modern-source-to-source-transformation-with-clang-and-libtooling> & <http://amnoid.de/tmp/clangtut/tut.html>
  * 基于clang的C内存安全语法增强，<https://github.com/microsoft/checkedc> & <https://github.com/microsoft/checkedc/wiki>
  * GPU性能优化参数影响：<https://github.com/ROCm/Tensile/wiki/Kernel-Parameters>


## Others

* 组织结构和治理
  * 关于组织结构的思考：Complexity Rising: From Human Beings to Human Civilization, a Complexity Profile,  <https://www.researchgate.net/publication/250082400_Complexity_Rising_From_Human_Beings_to_Human_Civilization_a_Complexity_Profile>
  * 公司治理结构：<https://www.ceibs.edu/facultyCV/lneng/ch3%20two%20stories%20and%20a%20model%205%204%2099.pdf>
  * OpenAI与DeepMind的scaling laws之争：<https://www.huxiu.com/article/2752424.html>
    * "幂律"是指 两个变量中的一个变量 与 另一个变量的某个幂次 成 正比
    * 类似的规律在书《规模》中有类似的探讨
  * 关于《规模》的思考：<https://baijiahao.baidu.com/s?id=1666179110447958325&wfr=spider&for=pc>
    * 这里面有一个有意思的系数：3/4，非严格证明，身体的代谢率与体重之间的关系。代谢率和体重的四分之三次方成正比，脑容量跟体重的四分之三次方成正比，心率和体重的负四分之一次方成正比，等等。类似的统计数据还有很多。它们都离不开一个数字，四。从分形的理论出发，结合人体血管系统特点，从分形的角度看，人体的某些身体结构，确切地说，是身体里的血管结构，是个分形的。从而说明人体的组织结构是“四”维的。进而说明里分母中4这个数字的来源。
    * 进一步演绎出城市、企业和规模之间的关系
    * > 一个组织真正的优势，不是规模大，而是，`规模复杂`。这就是要说的第三个问题，一个组织的成长，到底遵循着什么样的逻辑？答案很明确。不管是对个人、公司，还是城市来说，大，只一个基础，它不是真正的厉害。能够包容万物，能够有多样性的大，才是真的了不起。
  * 提高思考效率的50个模型，生命周期理论：<https://baijiahao.baidu.com/s?id=1784630212102007171&wfr=spider&for=pc>
* 产品
  * 王慧文清华产品课：<https://zhuanlan.zhihu.com/p/476319074>


## Research

* How to Look for Ideas in Computer Science Research: <https://medium.com/digital-diplomacy/how-to-look-for-ideas-in-computer-science-research-7a3fa6f4696f>
* Design Patterns for Research Methods: Iterative Field Research, <https://kpratt.net/wp-content/uploads/2009/01/research_methods.pdf>
* Research Patterns by Prof. Philip Guo
