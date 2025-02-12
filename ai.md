# AI



## GPU

[高性能芯片（3A090）及包含该等芯片的计算机、电子组件和部件（4A090）](https://www.hankunlaw.com/portal/article/index/cid/8/id/13998.html)  
1007规则在CCL中新增了一系列高性能芯片相关物项的ECCN，其中包括高性能芯片（3A090）及包含该等芯片的计算机、电子组件和部件（4A090）。  
1007规则出台后，英伟达的A100和H100芯片均符合相应ECCN项下的技术参数，从而落入出口管制范围。  
为了规避出口管制，英伟达推出特供中国的A800和H800芯片，在传输速率上有所降低，从而能够绕开1007规则项下的技术参数，但在算力上并没有区别。  
BIS为了应对该等技术规避行为，在1017规则中调整了高性能芯片的技术参数，放弃了传输速率，引入了性能密度，从而扩展了3A090所包含的高性能芯片的范围。  
1017规则项下高性能芯片的技术参数如下：  
第一级：总处理性能≥4,800；或总处理性能≥1,600，且性能密度≥5.92  
第二级：4,800＞总处理性能≥2,400，且5.92＞性能密度≥1.6；或总处理性能≥1,600，且5.92＞性能密度≥3.2  
"总处理能力" (Total Processing Power, TPP)  
"性能密度" (Performance Density，即TPP分数除以芯片尺寸即可得到的数字）	  

	 
[H200(4nm)](https://resources.nvidia.com/en-us-data-center-overview-mc/en-us-data-center-overview/hpc-datasheet-sc23-h200)  
TSMC 4N process	  
1,979 TFLOPS  
34 TFLOPS@FP64  
67 TFLOPS@FP64 Tensor Core  
67 TFLOPS@FP32  
989 TFLOPS@TF32 Tensor Core*  
1,979 TFLOPS@BFLOAT16 Tensor Core*  
1,979 TFLOPS@FP16 Tensor Core*  
3,958 TFLOPS@FP8 Tensor Core*  
3,958 TFLOPS@INT8 Tensor Core*  
141GB HBM3e, 4.8TB/s   
NVIDIA NVLink™: 900GB/s  
PCIe Gen5  
700W  

	
[H100(4nm)](https://resources.nvidia.com/en-us-gpu-resources/h100-datasheet-24306?lx=CPwSfP)  
TSMC 4N process, 80 billion transistors, a die size of 814 mm2  
1,979 TFLOPS  
34 TFLOPS@FP64  
67 TFLOPS@FP64 Tensor Core  
67 TFLOPS@FP32  
989 TFLOPS@TF32 Tensor Core*  
1,979 TFLOPS@BFLOAT16 Tensor Core*  
1,979 TFLOPS@FP16 Tensor Core*  
3,958 TFLOPS@FP8 Tensor Core*  
3,958 TFLOPS@INT8 Tensor Core*  
80GB HBM3, 3.35TB/s   
NVIDIA NVLink™: 900GB/s	  
PCIe Gen 5	 
700W	

	
[A100(7nm)](https://resources.nvidia.com/en-us-gpu-resources/nvidia-a100-datashee-1?lx=CPwSfP)  
TSMC’s 7nm N7, 54.2 billion transistors with a die size of 826 mm2.	  
7 GPCs, 7 or 8 TPCs/GPC, 2 SMs/TPC, up to 16 SMs/GPC, 108 SMs  
64 FP32 CUDA Cores/SM, 6912 FP32 CUDA Cores per GPU  
4 Third-generation Tensor Cores/SM, 432 Third-generation Tensor Cores per GPU  
5 HBM2 stacks, 10 512-bit Memory Controllers	 
The A100 introduces third-generation Tensor Cores that support TF32  
9.7 TFLOPS@FP64  
19.5 TFLOPS@FP64 Tensor Core  
19.5 TFLOPS@FP32  
156 TFLOPS | 312 TFLOPS@TF32  
312 TFLOPS | 624 TFLOPS@BFLOAT16 Tensor Core  
312 TFLOPS | 624 TFLOPS@FP16 Tensor Core  
624 TOPS | 1248 TOPS@INT8 Tensor Core  
80GB HBM2e, 2,039GB/s  
PCIe Gen4	 
400W  


[V100(12nm)](https://www.nvidia.com/en-us/data-center/v100/)  
5120 CUDA cores, 640 Tensor Cores， The V100's Tensor Cores primarily support FP16 precision.  
TSMC 12 nm FFN 21,100 million 815 mm²  
7 TFLOPS@FP64  
14 TFLOPS@FP32  
28 TFLOPS@FP16  
120 TFOPS@FP16 Tensor Core  
16 GB HBM2 900 GB/s  
PCIe Gen3	  
250W  


[L40S](https://resources.nvidia.com/en-us-gpu-resources/proviz-partner-l40s?lx=CPwSfP)  
18,176 CUDA cores, 568 Tensor Cores  
362 TFLOPS  
91.6 TFLOPS@FP32  
183 TFLOPS | 366 TFLOPS@TF32  
362 TFLOPS | 733 TFLOPS@BFLOAT16 Tensor Core   
362 TFLOPS | 733 TFLOPS@FP16 Tensor Core  
733 TFLOPS | 1466 TFLOPS@FP8 Tensor Core  
733 TFLOPS | 1466 TFLOPS@INT8 Tensor Core   
733 TFLOPS | 1466 TFLOPS@INT4 Tensor Core  
48GB GDDR6, 864GB/s  
PCIe Gen4	 
350W  

[AMD Instinct™ MI325X(5nm)](https://www.amd.com/en/products/accelerators/instinct/mi300/mi325x.html)  
TSMC 5nm | 6nm FinFET, 153 Billion   
1.3 PFLOPs  
256 GB HBM3E, 6 TB/s  
PCIe® 5.0 x16	
1000W 
 
 
[Gaudi 3(5nm)]()
TSMC 5nm	 
1835 TFLOPS	  
128GB(2x 64GB) HBM2e，3.7TB/sec  
200Gb Ethernet  
900W  

	
[Gaudi 2(7nm)]()
TSMC 7nm	 
432 TFLOPS  	
96GB HBM2e, 2.45TB/sec  
200Gb Ethernet  
600W  

[华为昇腾910B](https://www.eet-china.com/mp/a259980.html)  
华为昇腾910B的能力已经基本达到英伟达A100的水平  
64GB HBM2E  
376 TFLOPS	 
PCIe 5.0 x16  
直出200Gb RoCE	  
400W  


[壁仞BR100](https://www.geekpark.net/news/306540)  
7nm，770 亿个晶体管，1000mm²  
64GB HBM2E  
1024 TFLOPS@BF16  
2048 TFLOPS@int8  
550W	

[壁仞BR104](https://www.geekpark.net/news/306540)  
7nm  
32GB HBM2E  
512 TFLOPS@BF16  
1024 TFLOPS@INT8  
300W	

[壁仞BR106](https://mp.weixin.qq.com/s/7FuHbhKFcRf1GGRv5Focig)  
7nm  
85 TFLOPS@TF16  
170 TFLOPS@BF16  
340 TFLOPS@INT8  
32GB HBM2E 819GB/s  
PCIe 5.0 x8  
400W	





[天数智芯天垓100(7nm)(兼容CUDA)](https://www.iluvatar.com/productDetails?fullCode=cpjs-yj-xlxl-tg100)  
7nm, 240亿晶体管  
37 TFLOPS@FP32  
147 TFLOPS@FP16  
295 TFLOPS@INT8  
32GB HBM2, 1.2TB/sec  
PCIe® 4.0 x16  
250W  

[天数智芯天垓150(兼容CUDA)](https://mp.weixin.qq.com/s/7FuHbhKFcRf1GGRv5Focig)  
45 TFLOPS@FP32  
190 TFLOPS@FP16  
380 TFLOPS@INT8  
64GB HBM2e, 1.2TB/sec  
PCIe® 4.0 x16  
350W  

[海光K100(兼容CUDA)](https://mp.weixin.qq.com/s/7FuHbhKFcRf1GGRv5Focig)  
24.5 TFLOPS@FP64	
24.5 TFLOPS@FP32	
100 TFLOPS@FP16  
200 TFLOPS@INT8  
64GB GDDR6  
PCIe® 4.0 x16  
300W	


[海光K100_AI(兼容CUDA)](https://mp.weixin.qq.com/s/7FuHbhKFcRf1GGRv5Focig)  
49/98 TFLOPS@FP32/TF32	
196 TFLOPS@FP16/BF16  
392 TFLOPS@INT8  
64GB GDDR6  
PCIe® 4.0 x16  
350W


[海光DCU100(兼容CUDA)](https://www.vzkoo.com/read/2024082266eda1c2a51eaf56d9404032.html)  
7nm  
10 TFLOPS@FP64	
12 TFLOPS@FP32  
32GB HBM2  
PCIe® 4.0 x16  
350W	


[沐曦羲云C500](https://www.vzkoo.com/read/2024082266eda1c2a51eaf56d9404032.html)  
15 TFLOPS@FP32	
120 TFLOPS@TF32  
240 TFLOPS@FP16/BF16  
480 TFLOPS@INT8  
64GB HBM2e  
PCIe® 5.0 x16  
350W	

	
[燧原云燧T21](https://support.enflame-tech.com/onlinedoc_hw/1-t2x/t21/product_manual/content/source/product-manual.html#id6)  
12nm?	
32GB HBM2E, 1.6TB/s  
PCIe 4.0 x16  
300W  


[摩尔线程MTT S4000](https://www.mthreads.com/product/S4000)   
25 TFLOPS@FP32  
50 TFLOPS@TF32
100 TFLOPS@FP16  
200 TOPS@INT8  
48 GB, 768 GB/s  
PCIe 5.0 x16  
450W  


[摩尔线程MTT S3000](https://www.mthreads.com/product/S3000)  
15.2 TFLOPS@FP32  
32GB GDDR6, 448GB/s  
PCIe 5.0 x16  
250W  

	
[寒武纪思元MLU370-X8](https://www.cambricon.com/index.php?m=content&c=index&a=lists&catid=406)  
7nm  
96 TFLOPS@FP16  
256 TOPS@INT8  
48GB LPDDR5 614.4 GB/s  
PCIe 4.0 x16  
250W  


[寒武纪思元MLU370-S4/S8](https://www.cambricon.com/index.php?m=content&c=index&a=lists&catid=365)  
7nm  
72 TFLOPS@FP16  
192 TOPS@INT8  
24GB/48GB LPDDR5 307.2 GB/s  
PCIe 4.0 x16  
75W  


## AI Server


[Supermicro GPU Servers](https://www.supermicro.com/en/products/gpu)  

[Lambda GPU Cloud, Clusters, Servers, Workstations ](https://lambdalabs.com/)  

[Lambda Scalar with NVIDIA H200 NVL GPUs](https://lambdalabs.com/scalar-h200-waitlist)
* 4U
* 8 GPUs from NVIDIA  
GPUs
  1. NVIDIA H200 NVL: 141 GB of HBM3e, 14,592 CUDA cores, 456 Tensor Cores, PCIe 5.0 x16
  2. NVIDIA H100 NVL: 94 GB of HBM3, 14,592 CUDA cores, 456 Tensor Cores, PCIe 5.0 x16
  3. NVIDIA L40S: 48 GB of GDDR6, 18,176 CUDA cores, 568 Tensor Cores, PCIe 4.0 x16
  4. NVIDIA RTX 6000 Ada Generation: 48 GB of GDDR6, 18,176 CUDA cores, 568 Tensor Cores, PCIe 4.0 x16
  5. NVIDIA RTX 5000 Ada Generation: 32 GB of GDDR6, 12,800 CUDA cores, 400 Tensor Cores, PCIe 4.0 x16
  6. NVIDIA RTX 4500 Ada Generation: 24 GB of GDDR6, 7,680 CUDA cores, 240 Tensor Cores, PCIe 4.0 x16
  7. NVIDIA RTX 4000 Ada Generation: 16 GB of GDDR6, 6,144 CUDA cores, 192 Tensor Cores, PCIe 4.0 x16
* 192 cores and 384 threads  
  1. AMD EPYC 7004 (Genoa) Series Processors with up to 192 cores total
  2. Intel Xeon 4th Gen (Sapphire Rapids) Scalable Processors with up to 112 cores total
* 8192 GB of memory  
   Up to 8 TB of 4800 MHz DDR5 ECC RAM in 32 DIMM slots
* 491 TB of NVMe SSDs  
   Up to 491.52 TB of storage via 16 hot-swappable U.2 NVMe SSDs...
* Built-in networking:  
  1. 2 RJ45 10 Gbps BASE-T LAN ports
  2. 1 RJ45 1 Gbps BASE-T LAN out-of-band management port
* Optional high-speed NIC. Options include:  
  1. NVIDIA ConnectX-7 400 Gb/s NDR InfiniBand Adapter, OSFP56, PCIe 5.0 x16
  2. NVIDIA ConnectX-7 200 Gb/s NDR200 InfiniBand Adapter, OSFP56, PCIe 5.0 x16
  3. NVIDIA ConnectX-7 200 Gb/s NDR200 InfiniBand/VPI Adapter, QSFP112, PCIe 5.0 x16
  4. NVIDIA ConnectX-6 200 Gb/s HDR InfiniBand/VPI Adapter, QSFP56, PCIe 4.0 x16
  5. NVIDIA ConnectX-6 100 Gb/s HDR100 InfiniBand/VPI Adapter, 1x QSFP56, PCIe 4.0 x16
  6. NVIDIA ConnectX-6 Dx EN 200 Gb/s Ethernet Adapter, QSFP56, PCIe 4.0 x16
  7. NVIDIA ConnectX-6 Dx EN 100 Gb/s Ethernet Adapter, QSFP56, PCIe 4.0 x16
  8. NVIDIA ConnectX-5 EN 100 Gb/s Ethernet Adapter, QSFP28, PCIe 3.0 x16





[浪潮NF5468M5]()  
8xPCle 3.0 FHFLDW, 4xPCle 3.0 FHHLSW  

[浪潮NF5468M6-P](https://www.ieisystem.com/product/ai/8629.html)  
支持2颗全新一代英特尔® 至强® Icelake可扩展处理器	
8xPCle 4.0 FHFLDW, 4xPCle 4.0 FHHLSW  

[浪潮NF5468-M7](https://www.ieisystem.com/product/ai/11286.html)  
支持2颗英特尔®第四代/第五代至强®可扩展处理器  
支持8颗全高全长双宽PCIe接口GPU卡，同时支持≥4个PCIe 5.0 x16插槽  

[浪潮NF5468A5](https://www.ieisystem.com/product/ai/10694.html)  
支持2颗AMD EPYC处理器，TDP 280W，最高支持3 xGMI互联  
支持8个PCIe接口的GPU卡，TDP 350W  
支持2个PCIe 4.0 x16，1个OCP3.0  

[浪潮NF5688-M7](https://www.ieisystem.com/product/ai/15080.html)  
2颗Intel®第四代/第五代至强®可扩展处理器,TDP 350W  
1块NVIDIA HGX-Hopper-8GPU模组  
支持10个PCIe 5.0 x16插槽（其中1个PCIe 5.0 x16插槽可替换为2个PCIe 5.0 x8速率的x16槽位）  

[浪潮NF5698G7](https://www.ieisystem.com/product/ai/14951.html)  
6U 
8颗符合OAMv1.1/v1.5规范的开放加速模块，最大TDP 700W  
2颗Intel®第四代/第五代至强®可扩展处理器,TDP 350W  
支持10个PCIe 5.0 x16插槽（其中1个PCIe 5.0 x16插槽可替换为2个PCIe 5.0 x8速率的x16槽位）  可选支持Blueﬁeld-3、CX7以及多种类型智能网卡  

[新华三DL380a Gen11](https://www.h3c.com/cn/Products_And_Solution/Server/HPE/Products/GPU_Server/Products_Series/DL380a_Gen11/)  
2U  
支持2颗第四代Sapphire Rapids或第五代Emerald Rapids英特尔®至强®可扩展处理器，单颗多达64个核心，最大功率350W  
支持4个PCIe 5.0插槽、支持2个x16 OCP 3.0插槽  

[新华三Apollo_6500_Plus](https://www.h3c.com/cn/Products_And_Solution/Server/HPE/Products/GPU_Server/Products_Series/Apollo_6500_Plus/)  
6U  
HPE ProLiant XL645d 计算节点  
每个节点为单个AMD EPYC 7002/7003 系列处理器，可支持最高频率和核数的功耗达280W  
支持NVIDIA HGX A100 4-GPU  
HPE ProLiant XL675d 计算节点  
单个节点为支持两个AMD EPYC 7002/7003 系列处理器，可支持最高频率和核数的功耗达280W  
支持NVIDIA HGX A100 8-GPU  

[宁畅X680 G55](https://www.nettrix.com.cn/product/1590.html)  
8U  
支持2颗第四代/第五代英特尔® 至强® 可扩展处理器，TDP 350W  
支持NVLink GPU 8个	  
最大可配置9个PCIe 5.0 1个OCP 1个 RAID卡专用插槽	 

[宁畅X640 G50](https://www.nettrix.com.cn/product/1591.html)  
4U  
支持2颗第四代/第五代智能英特尔® 至强® 可扩展处理器，TDP 350W  
最大可配置12个PCIe 5.0扩展插槽，最大支持 10个双宽GPU	  

[宁畅X620 G50](https://www.nettrix.com.cn/product/1575.html)  
2U  
支持2颗第四代/第五代英特尔® 至强® 可扩展处理器，TDP 385W  
最大可配置9个PCIe 5.0扩展插槽，包含1个OCP插槽，最大支持4个双宽GPU或6个单宽GPU  

[宁畅X660 G45](https://www.nettrix.com.cn/product/1571.html)  
6U  
支持2颗第三代智能英特尔®至强®可扩展处理器  
8个NVIDIA®Tesla®SXM4 A800 （液冷专用）  
最大支持10个PCI-E4.0插槽（支持1个OCP）  

[宁畅X640 G40](https://www.nettrix.com.cn/product/1555.html)  
4U  
支持2颗第三代智能英特尔®至强®可扩展处理器  
最大支持20个PCI-E4.0插槽  
-（支持一个OCP网卡，支持≥4个PCIe 4.0全高全长扩展插槽，其中PCIe X16插槽8个）  

[宁畅X620 G40](https://www.nettrix.com.cn/product/1553.html)  
2U  
支持2颗第三代智能英特尔®至强®可扩展处理器  
最大支持10个PCIe 4.0 x16插槽（包含1个OCP网卡），支持PCIe 4.0全高全长扩展插槽	  





## RNIC


[Mellanox MCX715105AS-WEAT ConnectX®-7](https://docs.nvidia.com/networking/display/connectx7vpi)  
Adapter Card Size: 167.65mmx 68.90mm  
Ethernet: 1x400GbE  
Interface Type: QSFP112  
Host Interface: PCIe 5.0 x16  

[Ethernet Protocols supported by the electrical interface](https://docs.nvidia.com/networking/display/nvidia-connectx-7-adapter-cards-user-manual.pdf)  
400GAUI-4 C2M, 400GBASE-CR4 , 200GAUI-2 C2M, 200GAUI-4 C2M, 200GBASE-CR4, 100GAUI-2 C2M, 100GAUI-1 C2M, 100GBASE-CR4, 100GBASE-CR2, 100GBASE-CR1, 50GAUI-2 C2M, 50GAUI-1 C2M, 50GBASE-CR, 50GBASE-R2 , 40GBASE-CR4, 40GBASE-R2, 25GBASE-R, 10GBASE-R, 10GBASECX4, 1000BASE-CX, CAUI-4 C2M, 25GAUI C2M,XLAUI C2M , XLPPI, SFI  


[Mellanox MCX653105A-HDAT ConnectX®-6](https://docs.nvidia.com/networking/display/connectx6vpi)  
Adapter Card Size: 167.65mmx 68.90mm  
Ethernet: 1x200GbE  
Interface Type: QSFP56	 
Host Interface: PCIe 4.0 x16  

[Ethernet Protocols supported by the electrical interface](https://docs.nvidia.com/nvidia-connectx-6-infiniband-ethernet-adapter-cards-user-manual.pdf)  
200GBASE-CR4, 200GBASE-KR4, 200GBASE-SR4, 100GBASE-CR4, 100GBASE-CR2, 100GBASE-KR4, 100GBASE-SR4, 50GBASE-R2, 50GBASE-R4, 40GBASE-CR4, 40GBASE-KR4, 40GBASE-SR4, 40GBASE-LR4, 40GBASE-ER4, 40GBASE-R2, 25GBASE-R, 20GBASE-KR2, 10GBASE-LR,10GBASE-ER, 10GBASE-CX4, 10GBASE-CR, 10GBASEKR, SGMII, 1000BASE-CX, 1000BASE-KX, 10GBASE-SR  


[Mellanox MCX516A-CDAT](https://docs.nvidia.com/networking/display/connectx5en)  
Adapter Card Size: 142.24 mm x 68.90mm  
Ethernet: 2x100GbE  
Interface Type: QSFP28	
Host Interface: PCIe 3.0 x16  


[AMD Pollara 400](https://www.amd.com/content/dam/amd/en/documents/pensando-technical-docs/product-briefs/pensando-pollara-400-product-brief.pdf)  
400 Gbps  
QSFP112 (NRZ/PAM4 Serdes)  
Half-height, half-length (HHHL)  
PCIe Gen5.0 x16  
P4 Programmability  
Multipathing & Intelligent Packet Spraying  
In-Order Message Delivery  
Fast Loss Recover with Selective Retransmission  
Path Aware Congestion Control  
Rapid Fault Detection in High-Performance AI Networks  

[DreamBig Mercury](https://dreambigsemi.com/mercury-ai-supernic/)
800G AI-SuperNIC chip (Mercury) with Fully HW Offloaded RoCE v2 + UEC RDMA Engine  
Multi-pathing and packet spraying  
Out-of-order packet placement with in-order message delivery  
Programmable congestion control for RoCE v2 and UEC algorithms  
Advanced packet trimming and telemetry congestion notifications  
Support for selective retransmission  
Mercury provides UEC-compliant software drivers enabling GPU-to-GPU communication with exceptional throughput and minimal latency.  

	

[云脉芯联metaConnect-200](https://www.yunsilicon.com/#/productInformation)  
Adapter Card Size: 167.65mmx 68.90mm  
Ethernet: 2x100GbE  
Interface Type: QSFP28/56	  
Host Interface: PCIe 4.0 x16  
RoCEv2： 可编程拥塞控制算法  
虚拟化能力：SRIOV  
存储： 支持百万级IOPS存储读写，支持多路径冗余备份  

[中科驭数FLEXFLOW®-2200R RDMA 网络DPU卡](https://www.yusur.tech/product/flexflow/flexflow2200r)  
Adapter Card Size: 167.65mmx 68.90mm  
Ethernet: 2x100GbE  
Interface Type: QSFP28  
Host Interface: PCIe 3.0 x16  
RoCEv2： 可编程拥塞控制算法  
虚拟化能力：SRIOV  
存储： NVME over RDMA  




## AI Switch
 
[xsightlabs X2](https://xsightlabs.com/wp-content/uploads/2024/09/X2-PB-Public.pdf)  
1. 12.8 Tbps full-duplex, non-blocking switching optimized for data centers, cloud, and AI networks.
2. 100 Gbps PAM4 LR SerDes supporting retimer-less designs.   
3. Application Optimized Switching architecture powered by a programmable packet header processor enabling high performance, low latency and low power.
4. X-PNDTM: Elastic resource allocation of control tables maximizing adaptation to application needs.
5. Fully shared packet buffer for incast burst handling.
6. Low latency with cut-through — 700ns first-bit-in-first-bit-out for typical data center applications.
7. X-IQTM: UEC-ready programmable congestion measurement and signalling to facilitate dynamic load balancing and fast failure detection and recovery.
8. X-LBTM: UEC-ready weighted congestion-aware dynamic load balancing for reducing tail latency.
9. X-FCTM: Incast tolerance mechanism with HoL Blocking prevention.


[bcm78900-series(5nm)](https://www.broadcom.com/products/ethernet-connectivity/switching/strataxgs/bcm78900-series)  
64 × 800GbE, 128 × 400GbE, or 256 × 200GbE ports  
Advanced adaptive routing, dynamic load balancing, and support for end-to-end congestion control capabilities specifically designed to handle the large, low entropy flows typical of AI/ML workloads
Hardware-based link failover for improved network resiliency and reduced JCT  
Six on-chip ARM processors for high-bandwidth, fully-programmable streaming telemetry and sophisticated embedded applications such as on-chip statistics summarization
Unmatched power efficiency, implemented as a monolithic 5nm die  


[bcm56990-series(7nm)](https://www.broadcom.com/products/ethernet-connectivity/switching/strataxgs/bcm56990-series)  
64 × 400GbE, 128 × 200GbE, 256 × 100GbE, 256 × 40GbE, 256 × 25GbE, or 256 × 10GbE  
The industry’s most advanced shared-buffer architecture, offering up to 10X higher incast absorption and providing the highest performance and lowest end-to-end latency for RoCEv2 workloads  
New advanced load balancing mechanisms, virtually eliminating hash polarization and providing extremely efficient, controllable link utilization  
Advanced congestion management, enabling new traffic management paradigms  
Four 1 GHz ARM processors for high-bandwidth, fully-programmable streaming telemetry and sophisticated embedded applications such as on-chip statistics summarization  
Implemented with unparalleled power efficiency in a monolithic 7nm die	  

	
[bcm56980-series](https://www.broadcom.com/products/ethernet-connectivity/switching/strataxgs/bcm56980-series)  
32x400GbE, 64x200GbE or 128x100GbE  
256 integrated SerDes with 56G-PAM4  
New Elephant Flow feature  
Dynamic Load Balancing and Dynamic Group Multipathing enhance ECMP  
New shared-buffer architecture offers 4X higher burst absorption and improved performance for ROCEv2 workloads  

[NVIDIA SN5400](https://www.naddod.com/products/nvidia-networking/102423)
Spectrum-4 based 400GbE 2U Open Ethernet switch with Cumulus Linux Authentication  
64x QSFP-DD 400GbE | 2x SFP28 25GbE  
25.6Tb/s  
Packet Buffer 160MB  
Intel x86 Xeon, Hexa-core Coffee Lake E-2276ME w/ secured-boot  
System Memory 32G  
Cumulus Linux  
$ 39650.00  

[NVIDIA SN5600](https://www.naddod.com/products/nvidia-networking/102424)
Spectrum-4 based 800GbE 2U Open Ethernet switch with Cumulus Linux Authentication  
64x OSFP 800GbE | 1x SFP28 25GbE  
51.2Tb/s  
Intel x86 Xeon, Hexa-core Coffee Lake E-2276ME w/ secured-boot  
System Memory 32G  
Cumulus Linux  
$ 55250.00  

[NVIDIA MQM9790-NS2R](https://www.naddod.com/products/nvidia-networking/102411)
32xOSFP 64x400Gb/s  
51.2Tb/s  
MLNX-OS  
System memory Single 8GB  
M.2 SSD SATA 16GB 2242 FF  
$ 24185.00  

[NVIDIA MQM9700-NS2F](https://www.naddod.com/products/nvidia-networking/102324)
32xOSFP 2x400Gb/s  
51.2Tb/s  
Latency 130ns  
x86 Coffee Lake i3  
System Memory 8GB  
$ 34898.00  


[NVIDIA MQM8790-HS2F](https://www.naddod.com/products/nvidia-networking/102389)
Quantum HDR InfiniBand Switch, 40 x HDR QSFP56 Ports  
40xQSFP56 200Gb/s  
16Tb/s  
130ns  
x86 ComEx Broadwell D-1508  
System Memory 8GB  
MLNX-OS  
$ 13120.00    


[NVIDIA MQM8700-HS2F](https://www.naddod.com/products/nvidia-networking/102172)
Quantum HDR InfiniBand Switch, 40 x HDR QSFP56 Ports  
40xQSFP56 200Gb/s  
16Tb/s  
130ns  
x86 ComEx Broadwell D-1508  
System Memory 8GB  
MLNX-OS  
$ 15776.00  

[NDD N9500-128QC](https://www.naddod.com/products/102323.html)
128x400G QSFP112  
Tomahawk 5/Broadcom BCM78900(5nm)  
51.2 Tbps  
Packet Buffer 165.2MB  
Intel Ice lake-D 1734NT (8Core)/1713NTE (4Core)    
DDR4：8GB x 2 SO-DIMM  
$ 37399.00  



[NDD N9200-64DC](https://www.naddod.com/products/102532.html)
64x400G QSFP-DD  
Tomahawk 4/Broadcom BCM56990  
25.6Tbps  
Packet Buffer 113.66 MB  
Intel® Xeon® Processor D-1548 8-Core 2.0 GHz  
DDR4: 16GB x 2 SO-DIMM  
$ 28699.00  






	
[Broadcom Tomahawk 5 Minipack3]()  

[Cisco G200-powered Cisco 8501]()  

[AIS800-32D](https://www.edge-core.com/product/ais800-32d/)
32 x QSFP-DD800 800GbE  
BCM78902 Tomahawk 5  
Intel® Xeon® Quad-Core 2.2 GHz  
32GB DDR4 SO-DIMM with ECC  
240GB m.2 2280 NVMe SSD  
64MB x 2  

[AIS800-64D](https://www.edge-core.com/product/ais800-64d/)  
Switch Ports: 64 x OSFP800 or QSFP-DD800 800GbE  
Port Modes:  
 1 x 800G (8 lanes 100G PAM4)  
 2 x 400G (4 lanes 100G PAM4) breakout  
 4 x 200G (2 lanes 100G PAM4) breakout  
 8 x 100G (1 lane 100G PAM4) breakout  
 1 x 400G (8 lanes 50G PAM4)  
 2 x 200G (4 lanes 50G PAM4) breakout  
 4 x 100G (2 lanes 50G PAM4) breakout  
 8 x 50G (1 lane 50G PAM4) breakout  
 1 x 100G (4 lanes 25G NRZ)  
Switch Silicon: BCM78900 Tomahawk 5  
Processor: Intel® Xeon® Processor D-1713NTE 4-Core 2.2 GHz  
SPI Flash: 64MB x 2  
Memory: 32GB DDR4 SO-DIMM with ECC  
Storage: 240G m.2 2280 NVMe SSD  

[Wedge100S-32X](https://www.edge-core.com/wp-content/uploads/2024/01/WedgeS-100-32X-R01.pdf)  
32 x QSFP28 ports in a compact 1RU form factor.
Each port supports 1 x 100 GbE/40 GbE, or 4 x 25 GbE/4 x 10 GbE/2 x 50 GbE via breakout cables.
Switch Silicon: Broadcom BCM56960 Tomahawk 3.2 Tbps
Broadwell-DE D1508 Processor 
8GB SO-DIMM DDR4 2400MHz with ECC
m.2 SSD 128GB


[CSP-7550](https://www.edge-core.com/product/csp-7550/)  
32 x 100GbE QSFP28 ports  
Dual processor sockets  
 Intel® Xeon® processor family  
 Up to 28 cores, 56 threads per socket    
 Improved performance of Intel® DPDK due to Intel® AVX-512  
8 DIMM slots per socket for DDR4 2133/2400/2666 MHz ECC LRDIMM or RDIMM  
4 open PCIe slots, 2 full-height (PCIe Gen3 x16) and 2 half-height (PCIe Gen3 x8)  
M.2 interface support NVMe PCIe3.0 x4 lane and SATA3.0  
*4 FPGA cards with Intel Stratix 10MX 8GB HMB2, 6x100GbE high speed connector (4 hard core 100GbE and optional 2 sost core IP).*

[AS9516-32D](https://www.edge-core.com/product/dcs810/)    
32 x 400G QSFP-DD switch ports with  Tofino2 BFN-T20-128Q  
Intel® Pentium® D-1517 4-Core 1.6GHz  
8GB SO-DIMM  
128GB M.2 SSD  


[MPT128](https://www.mestechs.com/barefoot/)    
32 x 400G QSFP-DD switch ports with  Tofino2 BFN-T20-128Q  
Intel® Pentium® D-1517 4-Core 1.6GHz  
8GB SO-DIMM  
128GB M.2 SSD  

[AS9716-32D](https://www.edge-core.com/product/dcs510/)  
32 x QSFP-DD 400 GbE  
BCM56980 Tomahawk 3  
Intel® Xeon® Processor D-1518 4-Core  
DDR4: 8 GB x 2 SO-DIMM  
SPI Flash: 16 MB x 2  
m.2 SSD: 50G MLC x 1  

[Wedge 100BF-32X](https://www.edge-core.com/product/dcs800/)  
32 x QSFP28 ports. Each port supports 1x25/40/50/100 GbE or 4 x 10/25 GbE per port using breakout cables  
Intel Tofino BFN-T10-032D (Dual pipeline)  
Intel® Pentium® D-1517  
8 GB SO-DIMM DDR4 RAM  
16 MB SPI Flash  
128 GB M.2 SSD 

[星融元X732Q-T](https://asterfusion.com/product/x3-t/)  
32 x 400GE QSFP-DD  

[星融元X564P-T](https://asterfusion.com/product/x3-t/)  
64 x 100GE/40GE QSFP28/QSFP+  


[星融元X532P-T](https://asterfusion.com/product/x3-t/)  
32 x 100GE/40GE QSFP28/QSFP+ 

[星融元X308P-48Y-T](https://asterfusion.com/product/x3-t/)  
48 x 25GE SFP28, 8 x 100GE/40GE QSFP28/QSFP+  

[华为CloudEngine XH16800](https://e.huawei.com/cn/products/switches/data-center-switches/xh16800)  
接口板(-J2 系列)  
XH-L36DQ2CQJ2 36 端口 400GE，2 端囗 100GE 以太网光接囗板(XHL-J2,QSFP-DD,QSFP28)  
XH-L40DQJ2 40 端口 400GE 以太网光接口板(XHL-J2,QSFP-DD)  
XH-L48CQJ2  48 端口 100GE 以太网光接口板(XHL-J2,QSFP28)  


[新华三S12500AI-18D48B-NCPK](https://www.h3c.com/cn/Products_And_Solution/InterConnect/Products/Switches/Products/Data_Center_Switch/Core_Switch/S12500/S12500AI/)  
440×760×88.1  
48x 200GE QSFP56端口  
18x 400GE QSFPDD端口  
支持VxLAN Mapping*支持RDMA无损网络RoCEv1/RoCEv2  
支持BUFFER可视化  
支持DCBX、PFC、ETS、ECN  
支持iNOF、IPCC*  
支持智能识别流量模型，动态调节AI ECN门限  


## 线缆

NRZ: non-return to zero  

PAM4: pulse-amplitude modulation 4-level(4 级脉冲幅度调制)  

比特率   
使用 NRZ 机制的传输将具有相同的波特率和比特率，因为一个符号可以携带一位。28Gbps（千兆每秒）比特率相当于 28GBdps（千兆每秒）波特率。同时，由于 PAM4 每个符号携带 2 位，56Gbps PAM4 将具有 28GBdps 的线路传输。因此，PAM4 将给定波特率的比特率比 NRZ 提高一倍，从而为 400G 等高速光传输带来更高的效率。更具体地说，400 Gbps 以太网接口可以使用 PAM4 调制实现 8 个 50Gbps 通道或 4 个 100Gbps 通道。

信噪比 (‌Signal to Noise Ratio, SNR) 和误码率 (Bit Error Ratio, BER)  
PAM4 的眼高是 NRZ 的 1/3，导致 PAM4 将 SNR（信噪比）提高 -9.54 dB（链路预算惩罚），这会影响信号质量并引入额外的高速信号的限制。垂直眼图开度小 33% 使PAM4 信号对噪声更敏感，从而导致更高的误码率。然而，PAM4 之所以成为可能，是因为前向纠错 (FEC) 可以帮助链接系统实现所需的 BER。


[1m (3ft) NVIDIA/Mellanox Compatible 400G QSFP-DD to 4 x 100G QSFP28 Ethernet Active Direct Attach Copper Breakout Cable](https://www.fs.com/products/139800.html?attribute=68263&id=1752199)
QDD-400G4Q4xNAC01  
US$2,499.00  
53.125Gbps (PAM4)  
25.78125Gbps (NRZ)  

[1m (3ft) NVIDIA/Mellanox MCP7H60-W001R30 Compatible 400G QSFP-DD to 2 x 200G QSFP56 Ethernet Passive Direct Attach Copper Breakout Cable](https://www.fs.com/products/101799.html?now_cid=3659)
US$109.00  


[PERCKO IB线缆AOC光纤堆叠线50G/200G/400G直连有源QSFP56/QSFP-DD带光模块Mellanox迈络思连接线可定制 400G转100G QSFP-DD转4*100G 1米](https://item.jd.com/10091923522838.html#crumb-wrap)
￥18768.00 

[PERCKO IB线缆AOC光纤堆叠线50G/200G/400G直连有源QSFP56/QSFP-DD带光模块Mellanox迈络思连接线可定制 400G转200G QSFP-DD转2*200G 1米](https://item.jd.com/10091923522830.html#crumb-wrap)
￥10848.00  





## 国产通用服务器

[浪潮NF3290G8](https://www.ieisystem.com/product/server/15942.html)    
2U  
1颗或2颗英特尔®至强® 6处理器（SRF-AP/GNR-AP），TDP 500W   
支持4个PCIe5.0 HHHL slot或者4x2.5寸硬盘，可选SAS/SATA/NVMe，支持热拔插  

[浪潮NF3280G8](https://www.ieisystem.com/product/server/15936.html)  
2U  
1颗AMD EPYC™ 9005系列处理器  
最大支持8个PCIe5.0扩展|支持2个OCP 3.0 网卡|最大支持4×DW GPU  

[浪潮NF5280M8](https://www.ieisystem.com/product/server/15922.html)  
2U  
1颗或2颗英特尔®至强®6处理器  
（后IO）最大支持15个PCIe 5.0扩展槽位，包括2个热插拔OCP 3.0  
可支持4个双宽GPU及8个单宽GPU  
