# Some papers on Generation of Chain-of-thought:

## COT Survey

[Beyond Chain-of-Thought: A Survey of Chain-of-X Paradigms for LLMs](https://arxiv.org/abs/2404.15676v2#:~:text=Chain-of-Thought%20(CoT)%20has%20been%20a%20widely)

[Navigate through Enigmatic Labyrinth  A Survey of Chain of Thought Reasoning: Advances, Frontiers and Future](https://arxiv.org/abs/2309.15402#:~:text=Notably,%20recent%20studies%20have%20revealed)



## Paper
| Paper  | Description | Link |
| ------------- | ------------- | -------------|
| Generating Chain-of-Thoughts with a Pairwise-Comparison Approach to  Searching for the Most Promising Intermediate Thought (ICML 2024)  | This paper proposes a pairwise comparison-based approach to generating chains of thoughts to find the most promising intermediate thinking. By comparing different thinking steps, the model is able to optimize its reasoning process to more efficiently generate coherent chains of thoughts to solve complex problems. | [arXiv](https://arxiv.org/abs/2402.06918#:~:text=In%20this%20paper,%20motivated%20by%20Vapnik's)|
| Tree of Thoughts: Deliberate Problem Solving with Large Language Models (NeurIPS 2023)  | This paper introduces a new “thinking tree” model that aims to enhance the problem solving ability of large language models by systematizing the thinking process. By structuring the thinking process into a tree structure, the model makes reasoning more organized, thus increasing the effectiveness and depth of problem solving. | [arXiv](https://arxiv.org/abs/2305.10601)|
| Chain-of-Thought Prompting Elicits Reasoning in Large Language Models (NeurIPS 2022)  | This thesis explores the effectiveness of chain-of-thought prompting to guide reasoning in large language models. It shows that using chain-of-thought prompts significantly enhances the model's reasoning ability, leading it to perform more accurately and reliably when dealing with complex tasks.
 | [arXiv](https://arxiv.org/abs/2201.11903)|
| Self-Consistency Improves Chain of Thought Reasoning in Language Models (ICLR 2023)  | This paper discusses how self-consistency improves chain of thought reasoning in language models. By introducing the self-consistency mechanism, the model is able to better correct its own reasoning process, thus generating a more consistent and accurate chain of thought reasoning and improving its ability to handle complex problems. | [arXiv](https://arxiv.org/abs/2203.11171#:~:text=Chain-of-thought%20prompting%20combined%20with)|
| Large Language Model Guided Tree-of-Thought (2023) | This paper proposes a tree-of-thought structure guided by a large language model, aiming to improve the efficiency and effectiveness of the model in problem solving. By combining the tree structure with the generative capabilities of the model, the research demonstrates how the model can be effectively guided to think deeply, thereby optimizing the problem solving process. | [arXiv](https://arxiv.org/abs/2305.08291)|


## Task and Dataset

<table>
  <tr>
    <th>Task</th>
    <th>Dataset</th>
    <th>Link</th>
    <th>Description</th>
  </tr>
  <tr>
    <td rowspan="18">Mathematical <br>Reasoning</td>
    <td>AddSub</td>
    <td>[arXiv]</td>
    <td>Simple arithmetic</td>
  </tr>
              <tr>
                <td>SingleEq</td>
                <td>[arXiv]</td>
                <td>Simple arithmetic</td>
              </tr>
              <tr>
                <td>MultiArith</td>
                <td>[arXiv]</td>
                <td>Simple arithmetic</td>
              </tr>
              <tr>
                <td>MAWPS</td>
                <td>[arXiv]</td>
                <td>Simple arithmetic</td>
              </tr>
              <tr>
                <td>AQUA-RAT</td>
                <td>[arXiv]</td>
                <td>Math reasoning with NL rationale</td>
              </tr>
              <tr>
                <td>ASDiv</td>
                <td>[arXiv]</td>
                <td>Multi-step math reasoning</td>
              </tr>
              <tr>
                <td>SVAMP</td>
                <td>[arXiv]</td>
                <td>Multi-step math reasoning</td>
              </tr>
              <tr>
                <td>GSM8K</td>
                <td>[arXiv]</td>
                <td>Multi-step math reasoning</td>
              </tr>
              <tr>
                <td>GSM-Hard</td>
                <td>[arXiv]</td>
                <td>GSM8K with larger number</td>
              </tr>
              <tr>
                <td>MathQA</td>
                <td>[arXiv]</td>
                <td>Annotated based on AQUA</td>
              </tr>
              <tr>
                <td>DROP</td>
                <td>[arXiv]</td>
                <td>Reading comprehension form</td>
              </tr>
              <tr>
                <td>TheoremQA</td>
                <td>[arXiv]</td>
                <td>Answer based on theorems</td>
              </tr>
              <tr>
                <td>TAT-QA</td>
                <td>[arXiv]</td>
                <td>Answer based on tables</td>
              </tr>
              <tr>
                <td>FinQA</td>
                <td>[arXiv]</td>
                <td>Answer based on tables</td>
              </tr>
              <tr>
                <td>ConvFinQA</td>
                <td>[arXiv]</td>
                <td>Multi-turn dialogs</td>
              </tr>
              <tr>
                <td>MATH</td>
                <td>[arXiv]</td>
                <td>Challenging competition math problems</td>
              </tr>
              <tr>
                <td>NumGLUE</td>
                <td>[arXiv]</td>
                <td>Multi-task benchmark</td>
              </tr>
              <tr>
                <td>LILA</td>
                <td>[arXiv]</td>
                <td>Multi-task benchmark</td>
              </tr>
  <tr>
    <td rowspan="11">Commonsense<br> Reasoning</td>
    <td>ARC</td>
    <td>[arXiv]</td>
    <td>Simple arithmetic</td>
  </tr>
              <tr>
                <td>OpenBookQA</td>
                <td>[arXiv]</td>
                <td>Open-book knowledges</td>
              </tr>
              <tr>
                <td>PIQA</td>
                <td>[arXiv]</td>
                <td>Physical commonsense knowledge</td>
              </tr>
              <tr>
                <td>CommonsenseQA</td>
                <td>[arXiv]</td>
                <td>Derived from ConceptNet</td>
              </tr>
              <tr>
                <td>CommonsenseQA 2.0</td>
                <td>[arXiv]</td>
                <td>Gaming annotation with high quality</td>
              </tr>
              <tr>
                <td>Event2Mind</td>
                <td>[arXiv]</td>
                <td>Intension commonsense reasoning</td>
              </tr>
              <tr>
                <td>McTaco</td>
                <td>[arXiv]</td>
                <td>Event temporal commonsense reasoning</td>
              </tr>
              <tr>
                <td>CosmosQA</td>
                <td>[arXiv]</td>
                <td>Narrative commonsense reasoning</td>
              </tr>
              <tr>
                <td>ComValidation</td>
                <td>[arXiv]</td>
                <td>Commonsense verification</td>
              </tr>
              <tr>
                <td>ComExplanation</td>
                <td>[arXiv]</td>
                <td>Commonsense explanation</td>
              </tr>
              <tr>
                <td>StrategyQA</td>
                <td>[arXiv]</td>
                <td>Multi-hop commonsense reasoning</td>
              </tr>

  <tr>
    <td rowspan="5">Symbolic<br> Reasoning</td>
    <td>Last Letter Concat</td>
    <td>[arXiv]</td>
    <td>Rule-based</td>
  </tr>
              <tr>
                <td>Coin Flip</td>
                <td>[arXiv]</td>
                <td>Rule-based</td>
              </tr>
               <tr>
                <td>Reverse List</td>
                <td>[arXiv]</td>
                <td>Rule-based</td>
              </tr>
               <tr>
                <td>BigBench</td>
                <td>[arXiv]</td>
                <td>Contains multiple symbolic reasoning datasets</td>
              </tr>
               <tr>
                <td>BigBench-Hard</td>
                <td>[arXiv]</td>
                <td>Contains multiple symbolic reasoning datasets</td>
              </tr>

  <tr>
    <td rowspan="6">Logical<br> Reasoning</td>
    <td>ReClor</td>
    <td>[arXiv]</td>
    <td>Questions from GMAT and LSAT</td>
  </tr>
              <tr>
                <td>LogiQA</td>
                <td>[arXiv]</td>
                <td>Questions from China Civil Service Exam</td>
              </tr>
               <tr>
                <td>ProofWriter</td>
                <td>[arXiv]</td>
                <td>Reasoning process generation</td>
              </tr>
               <tr>
                <td>FOLIO</td>
                <td>[arXiv]</td>
                <td>First-order logic</td>
              </tr>
               <tr>
                <td>DEER</td>
                <td>[arXiv]</td>
                <td>Inductive reasoning</td>
              </tr>
              <tr>
                <td>PrOntoQA</td>
                <td>[arXiv]</td>
                <td>Deductive reasoning</td>
              </tr>
</table>


## Method and Task
<table>
    <thead>
        <tr>
            <th rowspan="2"><strong>Method</strong></th>
            <th rowspan="2"><strong>Setting</strong></th>
            <th rowspan="2"><strong>Backbone</strong></th>
            <th colspan="4"><strong>Mathematical</strong></th>
            <th colspan="2"><strong>Commonsense</strong></th>
            <th colspan="2"><strong>Symbolic</strong></th>
        </tr>
        <tr>
            <th>GSM8K</th>
            <th>SVAMP</th>
            <th>Asdiv</th>
            <th>AQuA</th>
            <th>CSQA</th>
            <th>Strategy<br>QA</th>
            <th>LastLetter<br>Concat</th>
            <th>CoinFlip</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>I-O Prompting~<cite>[1]</cite></td>
            <td>fewshot</td>
            <td rowspan="5">text-davinci-002</td>
            <td>19.7</td>
            <td>69.9</td>
            <td>74</td>
            <td>29.5</td>
            <td>79.5</td>
            <td>65.9</td>
            <td>5.8</td>
            <td>49.0</td>
        </tr>
        <tr>
            <td>Fewshot CoT~<cite>[2]</cite></td>
            <td>fewshot</td>
            <td>63.1</td>
            <td>76.4</td>
            <td>80.4</td>
            <td>45.3</td>
            <td>73.5</td>
            <td>65.4</td>
            <td>77.5</td>
            <td>99.6</td>
        </tr>
        <tr>
            <td>PoT~<cite>[3]</cite></td>
            <td>fewshot</td>
            <td>80</td>
            <td>89.1</td>
            <td>-</td>
            <td>58.6</td>
            <td>-</td>
            <td>-</td>
            <td>-</td>
            <td>-</td>
        </tr>
        <tr>
            <td>Complex CoT~<cite>[4]</cite></td>
            <td>fewshot</td>
            <td>72.6</td>
            <td>-</td>
            <td>-</td>
            <td>-</td>
            <td>-</td>
            <td>77</td>
            <td>-</td>
            <td>-</td>
        </tr>
        <tr>
            <td>Automate CoT~<cite>[5]</cite></td>
            <td>fewshot</td>
            <td>49.7</td>
            <td>73.3</td>
            <td>74.2</td>
            <td>37.9</td>
            <td>76.1</td>
            <td>67.9</td>
            <td>58.9</td>
            <td>-</td>
        </tr>
        <tr>
            <td>Fewshot CoT~<cite>[2]</cite></td>
            <td>fewshot</td>
            <td rowspan="7">text-davinci-003</td>
            <td>66.83</td>
            <td>69.06</td>
            <td>-</td>
            <td>29.13</td>
            <td>-</td>
            <td>-</td>
            <td>-</td>
            <td>-</td>
        </tr>
        <tr>
            <td>PHP~<cite>[6]</cite></td>
            <td>fewshot</td>
            <td>79</td>
            <td>84.7</td>
            <td>-</td>
            <td>58.6</td>
            <td>-</td>
            <td>-</td>
            <td>-</td>
            <td>-</td>
        </tr>
        <tr>
            <td>Self-consistency~<cite>[7]</cite></td>
            <td>fewshot</td>
            <td>67.93</td>
            <td>83.11</td>
            <td>-</td>
            <td>55.12</td>
            <td>-</td>
            <td>-</td>
            <td>-</td>
            <td>-</td>
        </tr>
        <tr>
            <td>Active Prompt~<cite>[8]</cite></td>
            <td>fewshot</td>
            <td>65.6</td>
            <td>80.5</td>
            <td>79.8</td>
            <td>48</td>
            <td>78.9</td>
            <td>74.2</td>
            <td>71.2</td>
            <td>-</td>
        </tr>
        <tr>
            <td>Synthetic Prompt~<cite>[9]</cite></td>
            <td>fewshot</td>
            <td>73.9</td>
            <td>81.8</td>
            <td>80.7</td>
            <td>-</td>
            <td>-</td>
            <td>-</td>
            <td>-</td>
            <td>-</td>
        </tr>
        <tr>
            <td>FOBAR~<cite>[10]</cite></td>
            <td>fewshot</td>
            <td>79.5</td>
            <td>86</td>
            <td>-</td>
            <td>58.66</td>
            <td>-</td>
            <td>-</td>
            <td>-</td>
            <td>-</td>
        </tr>
        <tr>
            <td>Boosted Prompting~<cite>[11]</cite></td>
            <td>fewshot</td>
            <td>71.6</td>
            <td>-</td>
            <td>-</td>
            <td>55.1</td>
            <td>-</td>
            <td>-</td>
            <td>-</td>
            <td>-</td>
        </tr>
        <tr>
            <td>Fewshot CoT~<cite>[2]</cite></td>
            <td>fewshot</td>
            <td rowspan="7">code-davinci-002</td>
            <td>60.1</td>
            <td>75.8</td>
            <td>80.1</td>
            <td>39.8</td>
            <td>79</td>
            <td>73.4</td>
            <td>70.4</td>
            <td>99</td>
        </tr>
        <tr>
            <td>Self-Consistency~<cite>[7]</cite></td>
            <td>fewshot</td>
            <td>78</td>
            <td>86.8</td>
            <td>87.8</td>
            <td>52</td>
            <td>81.5</td>
            <td>79.8</td>
            <td>73.4</td>
            <td>99.5</td>
        </tr>
        <tr>
            <td>PAL~<cite>[12]</cite></td>
            <td>fewshot</td>
            <td>72</td>
            <td>79.4</td>
            <td>79.6</td>
            <td>-</td>
            <td>-</td>
            <td>-</td>
            <td>-</td>
            <td>-</td>
        </tr>
        <tr>
            <td>Resprompt~<cite>[13]</cite></td>
            <td>fewshot</td>
            <td>66.6</td>
            <td>-</td>
            <td>-</td>
            <td>45.3</td>
            <td>-</td>
            <td>-</td>
            <td>-</td>
            <td>-</td>
        </tr>
        <tr>
            <td>DIVERSE~<cite>[14]</cite></td>
            <td>fewshot</td>
            <td>82.3</td>
            <td>87</td>
            <td>88.7</td>
            <td>-</td>
            <td>79.9</td>
            <td>78.6</td>
            <td>-</td>
            <td>-</td>
        </tr>
        <tr>
            <td>Least-to-Most~<cite>[15]</cite></td>
            <td>fewshot</td>
            <td>68.01</td>
            <td>-</td>
            <td>-</td>
            <td>-</td>
            <td>-</td>
            <td>-</td>
            <td>94</td>
            <td>-</td>
        </tr>
        <tr>
            <td>Boosted Prompting~<cite>[11]</cite></td>
            <td>fewshot</td>
            <td>83.3</td>
            <td>88.6</td>
            <td>-</td>
            <td>61.7</td>
            <td>-</td>
            <td>-</td>
            <td>-</td>
            <td>-</td>
        </tr>
        <tr>
            <td>Fewshot CoT~<cite>[2]</cite></td>
            <td>fewshot</td>
            <td  rowspan="10">gpt-3.5-turbo</td>
            <td>76.5</td>
            <td>81.9</td>
            <td>-</td>
            <td>54.3</td>
            <td>78</td>
            <td>63.7</td>
            <td>73.2</td>
            <td>99</td>
        </tr>
        <tr>
            <td>Self-consistency~<cite>[7]</cite></td>
            <td>fewshot</td>
            <td>81.9</td>
            <td>86.4</td>
            <td>-</td>
            <td>62.6</td>
            <td>-</td>
            <td>-</td>
            <td>-</td>
            <td>-</td>
        </tr>
        <tr>
            <td>MetaCoT~<cite>[16]</cite></td>
            <td>fewshot</td>
            <td>75.1</td>
            <td>88.6</td>
            <td>-</td>
            <td>54.7</td>
            <td>72.4</td>
            <td>64.5</td>
            <td>77.2</td>
            <td>100</td>
        </tr>
        <tr>
            <td>Verify CoT~<cite>[17]</cite></td>
            <td>fewshot</td>
            <td>86</td>
            <td>-</td>
            <td>-</td>
            <td>69.5</td>
            <td>-</td>
            <td>-</td>
            <td>92.6</td>
            <td>-</td>
        </tr>
        <tr>
            <td>Active Prompting~<cite>[8]</cite></td>
            <td>fewshot</td>
            <td>81.8</td>
            <td>82.5</td>
            <td>87.9</td>
            <td>55.3</td>
            <td>-</td>
            <td>-</td>
            <td>-</td>
            <td>-</td>
        </tr>
        <tr>
            <td>RCoT~<cite>[18]</cite></td>
            <td>fewshot</td>
            <td>84.6</td>
            <td>84.9</td>
            <td>89.3</td>
            <td>57.1</td>
            <td>-</td>
            <td>-</td>
            <td>-</td>
            <td>-</td>
        </tr>
        <tr>
            <td>FOBAR~<cite>[10]</cite></td>
            <td>fewshot</td>
            <td>87.4</td>
            <td>87.4</td>
            <td>-</td>
            <td>57.5</td>
            <td>-</td>
            <td>-</td>
            <td>-</td>
            <td>-</td>
        </tr>
        <tr>
            <td>Memory-of-Thought~<cite>[19]</cite></td>
            <td>fewshot</td>
            <td>-</td>
            <td>-</td>
            <td>-</td>
            <td>54.1</td>
            <td>-</td>
            <td>-</td>
            <td>-</td>
            <td>-</td>
        </tr>
        <tr>
            <td>Adaptive-consistency~<cite>[20]</cite></td>
            <td>fewshot</td>
            <td>82.7</td>
            <td>85</td>
            <td>83</td>
            <td>-</td>
            <td>-</td>
            <td>67.9</td>
            <td>-</td>
            <td>-</td>
        </tr>
        <tr>
            <td>Boosted Prompting~<cite>[11]</cite></td>
            <td>fewshot</td>
            <td>87.1</td>
            <td>-</td>
            <td>-</td>
            <td>72.8</td>
            <td>-</td>
            <td>-</td>
            <td>-</td>
            <td>-</td>
        </tr>
        <tr>
            <td>Zeroshot CoT~<cite>[21]</cite></td>
            <td>zeroshot</td>
            <td >text-davinci-002</td>
            <td>40.5</td>
            <td>63.7</td>
            <td>-</td>
            <td>31.9</td>
            <td>64</td>
            <td>52.3</td>
            <td>57.6</td>
            <td>87.8</td>
        </tr>
        <tr>
            <td>PoT~<cite>[3]</cite></td>
            <td>zeroshot</td>
            <td>text-davinci-002</td>
            <td>57</td>
            <td>70.8</td>
            <td>-</td>
            <td>43.9</td>
            <td>-</td>
            <td>-</td>
            <td>-</td>
            <td>-</td>
        </tr>
        <tr>
            <td>AutoCoT~<cite>[22]</cite></td>
            <td>zeroshot</td>
            <td>text-davinci-002</td>
            <td>47.9</td>
            <td>69.5</td>
            <td>-</td>
            <td>36.5</td>
            <td>74.4</td>
            <td>65.4</td>
            <td>59.7</td>
            <td>99.9</td>
        </tr>
        <tr>
            <td>COSP~<cite>[23]</cite></td>
            <td>zeroshot</td>
            <td>code-davinci-001</td>
            <td>8.7</td>
            <td>-</td>
            <td>-</td>
            <td></td>
            <td>55.4</td>
            <td>52.8</td>
            <td>-</td>
            <td>-</td>
        </tr>
        <tr>
            <td>Plan-and-Solve~<cite>[24]</cite></td>
            <td>zeroshot</td>
            <td>text-davinci-003</td>
            <td>58.2</td>
            <td>72</td>
            <td>-</td>
            <td>42.5</td>
            <td>65.2</td>
            <td>63.8</td>
            <td>64.8</td>
            <td>96.8</td>
        </tr>
        <tr>
            <td>Agent-Instruct~<cite>[25]</cite></td>
            <td>zeroshot</td>
            <td>gpt-3.5-turbo</td>
            <td>73.4</td>
            <td>80.8</td>
            <td>-</td>
            <td>57.9</td>
            <td>74.1</td>
            <td>69</td>
            <td>99.8</td>
            <td>95.2</td>
        </tr>
        <tr>
            <td>Self-Refine~<cite>[26]</cite></td>
            <td>zeroshot</td>
            <td>gpt-3.5-turbo</td>
            <td>64.1</td>
            <td>-</td>
            <td>-</td>
            <td>-</td>
            <td>-</td>
            <td>-</td>
            <td>-</td>
            <td>-</td>
        </tr>
        <tr>
            <td>RCoT~<cite>[18]</cite></td>
            <td>zeroshot</td>
            <td>gpt-3.5-turbo</td>
            <td>82</td>
            <td>79.6</td>
            <td>86</td>
            <td>55.5</td>
            <td>-</td>
            <td>-</td>
            <td>-</td>
            <td>-</td>
        </tr>
    </table>
    <caption>The performance of various XoT methods in commonly used mathematical, commonsense and symbolic reasoning benchmarks. It is worth noting that, due to variations in the experimental setups of different methods, their performances are not directly comparable. The table is used to provide an overall empirical insight.</caption>
</div>









## Methods
| Method  | Description | Link |
| ------------- | ------------- | -------------|
| Direct  | - | [arXiv]|
| CoT  | - | [arXiv]|
| SC-CoT  | - | [arXiv]|
| SToT  | - | [arXiv]|
| ------------- | ------------- | -------------|
| SC-SToT | - | [arXiv]|
| Comp-SToT | - | [arXiv]|
| SC-SToT | - | [arXiv]|
| Back-SToT | - | [arXiv]|
| C-ToT (Stand.) | - | [arXiv]|
| C-ToT (Duel.) | - | [arXiv]|


## Datasets
| Dataset  | Description | Link |
| ------------- | ------------- | -------------|
| AQuA  | - | [arXiv]|
| Gsm8k  | - | [arXiv]|
| Coin Flip (OOD)  | - | [arXiv]|
| BBH | - | [arXiv]|
| CSQA | - | [arXiv]|
| StrategyQA | - | [arXiv]|
| Date | - | [arXiv]|
| Sports | - | [arXiv]|
| SayCan | - | [arXiv]|



## Task
| Task  | Description | Link |
| ------------- | ------------- | -------------|
| QA  | - | [arXiv]|
| Game of 24  | - | [arXiv]|
| Sudoku Puzzle | - | [arXiv]|
| Arithmetic reasoning | - | [arXiv]|
| Commonsense reasoning | - | [arXiv]|
| Symbolic Reasoning | - | [arXiv]|






