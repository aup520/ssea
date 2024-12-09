<html>

<head>
    <link rel="StyleSheet" href="style.css" type="text/css" media="all">
    <title>SSEAT</title>
    <!-- Place this tag in your head or just before your close body tag. -->
    <script async defer src="https://buttons.github.io/buttons.js"></script>
</head>
<body>
    <br>
    <div class="center-div" align="center">
        <span style="font-size:28px">Sustainable Self-evolution Adversarial Training</span>
    </div>

    <br>
    <table align="center" width="1000px">
        <tbody>
            <tr>
                <td align="center" width="180px">
                    <div class="center-div">
                        <span style="font-size:18px"><a href="https://wxwangiris.github.io/" target="_blank">Wenxuan Wang</a></span>
                    </div>
                </td>

                <td align="center" width="150px">
                    <div class="center-div">
                        <span style="font-size:18px"><a href="https://github.com/aup520" target="_blank">Chenglei Wang</a></span>
                    </div>
                </td>
                
                <td align="center" width="150px">
                    <div class="center-div">
                        <span style="font-size:18px"><a href="https://github.com/Galaxy-001" target="_blank">Huihui Qi</a></span>
                    </div>
                </td>

                <td align="center" width="150px">
                    <div class="center-div">
                        <span style="font-size:18px"><a href="https://yehaohao.github.io/academicpages.github.io/" target="_blank">Menghao Ye</a></span>
                    </div>
                </td>

                <td align="center" width="150px">
                    <div class="center-div">
                        <span style="font-size:18px"><a href="https://naiq.github.io/" target="_blank">Xuelin Qian</a></span>
                    </div>
                </td>

                <td align="center" width="150px">
                    <div class="center-div">
                        <span style="font-size:18px"><a href="https://scholar.google.com.au/citations?user=aPLp7pAAAAAJ&hl=en" target="_blank">Peng Wang</a></span>
                    </div>
                </td>

                <td align="center" width="150px">
                <div class="center-div">
                    <span style="font-size:18px"><a href="https://dblp.uni-trier.de/pid/14/6655.html" target="_blank">Yanning Zhang</a></span>
                </div>
                </td>

            </tr>
        </tbody>
    </table>
    <br>
    <table align="center" width="700px">
        <tbody>
            <tr>
                <td align="center" width="100px">
                    <div class="center-div">
                        <span style="font-size:18px">Northwestern Polytechnical University</span>
                    </div>
                </td>
            </tr>
        </tbody>
    </table>

    <br>

    <hr>
    <div class="center-div" align="center">
        <h2>Abstract</h2>
    </div>
    <table align="center" width="1000px">
        <td>
            <div>
            <span style="font-size:18px"> With the wide application of deep neural network models in various computer vision tasks, there has been a proliferation of adversarial example generation strategies aimed at deeply exploring model security. However, existing adversarial training defense models, which rely on single or limited types of attacks under a one-time learning process, struggle to adapt to the dynamic and evolving nature of attack methods. Therefore, to achieve defense performance improvements for models in long-term applications, we propose a novel Sustainable Self-Evolution Adversarial Training (SSEAT) framework. Specifically, we introduce a continual adversarial defense pipeline to realize learning from various kinds of adversarial examples across multiple stages. Additionally, to address the issue of model catastrophic forgetting caused by continual learning from ongoing novel attacks, we propose an adversarial data replay module to better select more diverse and key relearning data. Furthermore, we design a consistency regularization strategy to encourage current defense models to learn more from previously trained ones, guiding them to retain more past knowledge and maintain accuracy on clean samples. Extensive experiments have been conducted to verify the efficacy of the proposed SSEAT defense method, which demonstrates superior defense performance and classification accuracy compared to competitors.
            </div>
        </td>
       
    </table>
    <br><br>

    <hr>
    <div class="center-div" align="center">
        <h2>Overview</h2>
    </div>

    <table align="center" width="1000px">
        <td>
            <div>
            <span style="font-size:18px"> When confronted with the challenge of ongoing generated new adversarial examples in complex and long-term multimedia applications, existing adversarial training methods struggle to adapt to iteratively updated attack methods. In contrast, our SSEAT model achieves sustainable defense performance improvements by continuously absorbing new adversarial knowledge. 
            </div>
        </td>
    </table>

    <br>
    <table align="center">
        <tbody>
            <tr>
                <td>
                    <div class="center-div" align="center">
                        <a href="#"><img src="D:\paper\overview.png" width="600px"></a><br>
                    </div>
                </td>
            </tr>
            <tr>
                <td>
                    <div class="center-div" align="center">
                        <span style="font-size:16px"><i>A conceptual overview of SSEAT.</i>
                        </span></div>
                </td>
            </tr>
        </tbody>
    </table>
	<br>

    <table align="center" width="1000px">
        <td>
            <div>
            <span style="font-size:18px">Existing adversarial training models are difficult to resist diverse adversarial examples. It is essential for deep models to achieve sustainable
                improvement in defense performance for long-term application
                scenarios
            </div>
        </td>
    </table>
    <br><br>

	
	<hr> 
	<div class="center-div" align="center">
        <h2>SSEAT Framework</h2>
    </div>

    <table align="center" width="1000px">
        <td>
            <div>
            <span style="font-size:18px"> (a) Illustration of our Continual Adversarial Defense (CAD) pipeline. CAD helps the model to learn from new kinds of attacks in multiple stages continuously. (b) Illustration of our Adversarial Data Replay (ADR) module. ADR guides the model in selecting diverse and representative replay data to alleviate the catastrophic forgetting issue. (c) Illustration of our Consistency Regularization Strategy (CRS) component. CRS encourages the model to learn more from the historically trained models to maintain classification accuracy.
            </div>
        </td>
    </table>

    <br>
    <table align="center">
        <tbody>
            <tr>
                <td>
                    <div class="center-div" align="center">
                        <a href="#"><img src="D:\paper\framework.png" width="600px"></a><br>
                    </div>
                </td>
            </tr>
            <tr>
                <td>
                    <div class="center-div" align="center">
                        <span style="font-size:16px"><i>SSEAT framework</i>
                        </span></div>
                </td>
            </tr>
        </tbody>
    </table>
	
	<!-- <br>
	<table align="center" width="1000px">
        <td>
            <div>
            <span style="font-size:18px"> The file name in the folder is xxx_m or xxx_n, where xxx indicates the xxxth person, 
			"m" indicates the image with makeup, and "n" indicates the image without makeup. 
			This dataset is for non-commercial reseach purposes (such as academic research) only.
			<a href="https://drive.google.com/open?id=1wpqZCYh7gGKz897C-hQbgR7CHbJdBGxg">[Dataset Google Drive]</a>
            <a href="https://pan.baidu.com/s/1jhBqJeXShYyChfp1K3RcCw">[Dataset Baidu Drive](password:n2zw)</a>			
            </div>
        </td>
    </table>
	<br><br> -->

    <hr>
    <div class="center-div" align="center">
        <h2 id="paper">Paper and Data</h2>
    </div>
    <table align="center">

        <tbody>
            <tr>
                <td>
                    <img class="layered-paper-big" style="height:200px" src="D:\paper\paper.png">
                </td>
                <td>
					<b><span style="display:inline-block;width:600px;font-size:14pt">  Sustainable Self-evolution Adversarial Training
                    </span></b>
                    <br><br>
                    <span style="font-size:14pt">  Wenxuan Wang, Chenglei Wang, Huihui Qi, Menghao Ye, Xuelin Qian<sup>*</sup>, Peng Wang, Yanning Zhang</span>
                    <br><br>
                    <span style="font-size:14px">
                        <a href="https://openreview.net/forum?id=Ii5W5cQSMr">[Paper]</a>
                        <!--<a href="">[GitHub]</a>-->
                        <a href="https://github.com/aup520/SSEAT">[Code]</a>
                    </span>
                </td>
            </tr>
        </tbody>
    </table>
    <br><br>
	
	
	<hr> 
	<div class="center-div" align="center">
        <h2>Results</h2>
    </div>

    <br>
    <table align="center">
        <tbody>
            <tr>
                <td>
                    <div class="center-div" align="center">
                        <a href="#"><img src="D:\paper\result.png" width="650px"></a><br>
                    </div>
                </td>
            </tr>
        </tbody>
    </table>
	<br><br>

	<br>
    <table align="center">
        <tbody>
            <tr>
                <td>
                    <div class="center-div" align="center">
                        <a href="#"><img src="D:\paper\Visualization.png" width="700px"></a><br>
                    </div>
                </td>
            </tr>
            <tr>
                <td>
                    <div class="center-div" align="center">
                        <span style="font-size:16px"><i>Visualization result</i>
                        </span></div>
                </td>
            </tr>
        </tbody>
    </table>
	<br><br>
    
    <hr>
    <table align="center" width="980px">
        <tbody>
            <tr>
                <td>
                    <left>
                        <div class="center-div" align="center">
                            <h2>Acknowledgements</h2>
                        </div>
                        <div class="center-div" align="center"> 
                            The website is modified from this <a href="https://www.cs.cmu.edu/~wyuan1/pcn/">template</a>.
                        </div>
                    </left>
                </td>
            </tr>
        </tbody>
    </table>
    <br>



</body>

</html>
