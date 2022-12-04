---
layout: page
title: Tasks
permalink: /tasks/
---
<hr>
<br>
<div>
  <h2>Product Detection</h2>
    <div>
        The goal is to detect products as quadrilaterals from complex backgrounds. 
        Unitail-Det supports the training and evaluation.
        <br>
        For the each of the two test sets (cross-domain and origin-domain),
        you need to submit a Pickle file named “cross.pkl” or “origin.pkl”, respectively.
        The Pickle file is required to contain a dictionary following the format below <span>&#58;</span>
        <a href="https://drive.google.com/file/d/1ms6qfXEMafFxlCluyHrKOUWuK6zSoOlJ/view?usp=sharing">Submission Examples</a>
    </div>
    <table>
        <tr>
            <td>{
                <br>
                <p style="margin-left:1em">"imgs" <span>&#58;</span>                </p>
                <p style="margin-left:3em">   [test_x1.jpg,                       </p>
                <p style="margin-left:3em">    test_x2.jpg,                       </p>
                <p style="margin-left:3em">     ... ...,                            </p>
                <p style="margin-left:3em">    test_x3.jpg]                       </p>
                <p style="margin-left:1em">"quad"<span>&#58;</span>                 </p>
                <p style="margin-left:3em">   [<np.ndarray, float32> (n1, 9),   # results from 'test_x1.jpg'         </p>
                <p style="margin-left:3em">    <np.ndarray, float32> (n2, 9),       </p>
                <p style="margin-left:3em">     ... ...,                            </p>
                <p style="margin-left:3em">    <np.ndarray, float32> (n3, 9)]       </p>
                }
                <br>
                where each <np.ndarray, float32> contains n quadrilaterals in the order of (x1, y1, x2, y2, x3, y3, x4, y4, score) 
            </td>
        </tr>
    </table>
    The geometric mean of mean average precision (mAP) is calculated on the two testing set 
    as the primary metric.
</div>

<div>
    <h2>Text Detection</h2>
    <div>
        The goal is to detect text regions from pre-localized product images. 
        Unitail-OCR provides the training and testing. Like ICDAR 2015, no validation set is provided.
    </div>
</div>

<div>
    <h2>Text Recognition</h2>
    <div>
        The goal is to recognize words over a set of pre-localized text regions. 
        Unitail-OCR provides the training and testing. Like ICDAR 2015, no validation set is provided.
    </div>
</div>

<div>
    <h2>Product Matching</h2>
    <div>
        The goal is to recognize products by matching a set of query samples to the Unitail-OCR gallery. 
        The task is split into two tracks: 
        Hard Example Track, which is evaluated on 2.5k selected hard examples; 
        this track is designed for scenarios in which products are visually similar 
        (for example pharmacy stores); and General Track, which is conducted on all 10k samples.
        <br>
        A pickle file named "matchhard.pkl" or "matchgeneral.pkl" is required for the two tracks, respectively, 
        each should be following the format below <span>&#58;</span>
        <a href="https://drive.google.com/drive/folders/1h5_94cNQgth_k8F9M4Ur4dHGRzUAoM1N?usp=sharing">Submission Examples</a>
    </div>
    <table>
        <tr>
            <td>{
                <br>
                <p style="margin-left:1em">"imgs" <span>&#58;</span>                </p>
                <p style="margin-left:3em">   [test_x1.jpg,                       </p>
                <p style="margin-left:3em">    test_x2.jpg,                       </p>
                <p style="margin-left:3em">     ... ...,                            </p>
                <p style="margin-left:3em">    test_x3.jpg]                       </p>
                <p style="margin-left:1em">"cls" <span>&#58;</span>                 </p>
                <p style="margin-left:3em">   [c1(int64),   # results from 'test_x1.jpg'         </p>
                <p style="margin-left:3em">    c2(int64),       </p>
                <p style="margin-left:3em">     ... ...,                            </p>
                <p style="margin-left:3em">    c3(int64),       </p>
                }
                <br>
            </td>
        </tr>
    </table>
</div>



             
             
            
       


