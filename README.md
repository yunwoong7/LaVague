<h2 align="center">
Web Test Automation Using LaVague
</h2>

<div align="center">
  <img src="https://img.shields.io/badge/python-v3.11.8-blue.svg"/>
  <img src="https://img.shields.io/badge/llama_index-v0.10.20-blue.svg"/>
</div>

현대 비즈니스 환경에서 테스트 자동화는 소프트웨어 개발 과정의 핵심 요소로 자리 잡았습니다. 많은 기업들이 효율성과 정확성을 높이기 위해 다양한 테스트 자동화 도구를 도입해 왔습니다. 그러나 기존 개발 방식과 레거시 코드의 복잡성은 자동화 테스트의 적용을 어렵게 만들었습니다. 과거의 규정과 업무 변화에 급히 대응하며 추가된 예외 로직은 코드를 복잡하게 만들었고, 이로 인해 단위 테스트가 사실상 불가능해지는 상황에 이르렀습니다. Ui-Path나 Auto Anywhere와 같은 솔루션을 활용하는 시도도 있었지만, 이러한 도구들 역시 한계에 직면했습니다. 또한, Selenium을 이용한 자동화 접근 방식은 HTML 구조와 DOM에 대한 깊은 이해를 요구하며, 개발자에게 상당한 어려움을 줍니다.

개발자들은 더 나은 솔루션을 모색하게 되었고, 이 과정에서 자연어 명령을 브라우저 인터랙션(Selenium Code)으로 변환하여 브라우저를 자동화하는 Python 프레임워크가 등장했습니다.

[LaVague](https://github.com/lavague-ai/LaVague)는 기본적으로 사용자가 자연어만으로 웹 브라우저의 자동화 작업을 할 수 있도록 하는 AI 도구입니다. Selenium을 사용한 테스트 자동화를 개발할 때, HTML 구조와 DOM에 대한 깊은 이해가 필요했던 것과 달리, LaVague를 이용하면 이러한 복잡성을 대폭 줄여줍니다. 사용자는 복잡한 코딩 없이도 자연어로 자신이 원하는 웹 자동화를 설명하기만 하면 됩니다. 이는 기존의 개발 지식이 필요했던 부분을 AI가 해결해 주는 혁신적인 접근 방식입니다.

![img](https://blog.kakaocdn.net/dn/teTvr/btsF0lqigvR/beRuzKbRGnrOKYKaSyuqjK/img.gif)

물론, LaVague가 현재 초기 단계에 있기 때문에 아직 개선해야 할 부분이 많습니다. 그럼에도 불구하고, 생성형 AI를 활용한 이 방법은 웹 자동화 분야에서 매우 좋은 시도로 보입니다. 특히, LaVague의 현재 버전으로 다양한 테스트를 진행하면서 겪은 어려움을 직접 해결해 나가면서, 이 도구의 가능성과 한계를 보다 명확히 파악할 수 있었습니다.

---

### 추가 수정 내용

#### 다양한 LLM 모델 지원

이전에 초당 300 토큰을 처리할 수 있는 Groq의 빠른 플랫폼 API에 대해 설명드린 바 있습니다. 빠른 처리 능력을 가진 Groq API를 LaVague에서도 활용할 수 있도록 하였습니다.

- GROQ API("mixtral-8x7b-32768") 모델을 추가하여 선택할 수 있도록 하였습니다.
- Anthropic API("claude-3-haiku-20240307") 모델을 추가하여 선택할 수 있도록 하였습니다.
- 사용자는 필요에 따라 다양한 LLM 모델을 선택하여 사용할 수 있습니다.

#### 한글 명령 지원

기존에는 Gemma 모델만 사용하여 영문 명령만 처리할 수 있었습니다. 모델 추가로 인해 한글 명령도 지원하게 되었습니다. 사용자는 이제 한글로 명령을 입력하여 LaVague를 사용할 수 있습니다.

![img](https://blog.kakaocdn.net/dn/dXXZYC/btsF1LWye9A/m34odWEphdhcw4yqkzWf60/img.gif)

서두에서 언급했듯이, LaVague 프로젝트는 아직 초기 단계에 있으며, 완벽하게 작동하지 않는 경우도 종종 발생합니다. 이러한 초기 단계의 어려움에도 불구하고, 생성형 AI를 활용하여 웹 자동화를 달성하려는 LaVague의 접근 방식은 매우 유용한 시도 중 하나로 보입니다.

---

<p align="center">
  <a href="https://github.com/lavague-ai/LaVague/stargazers"><img src="https://img.shields.io/github/stars/lavague-ai/LaVague.svg?style=for-the-badge" alt="Stargazers"></a>
  <a href="https://github.com/lavague-ai/LaVague/issues"><img src="https://img.shields.io/github/issues/lavague-ai/LaVague.svg?style=for-the-badge" alt="Issues"></a>
  <a href="https://github.com/lavague-ai/LaVague/network/members"><img src="https://img.shields.io/github/forks/lavague-ai/LaVague.svg?style=for-the-badge" alt="Forks"></a>
  <a href="https://github.com/lavague-ai/LaVague/graphs/contributors"><img src="https://img.shields.io/github/contributors/lavague-ai/LaVague.svg?style=for-the-badge" alt="Contributors"></a>
  <a href="https://github.com/lavague-ai/LaVague/blob/master/LICENSE.md"><img src="https://img.shields.io/github/license/lavague-ai/LaVague.svg?style=for-the-badge" alt="Apache License"></a>
</p>

</br>

<div align="center">
  <img src="static/logo.png" width=140px: alt="LaVague Logo">
  <h1>Welcome to LaVague</h1>

<h4 align="center">
 <a href="https://discord.gg/SDxn9KpqX9" target="_blank">
    <img src="https://img.shields.io/badge/discord-000000?style=for-the-badge&colorB=555" height='35px' alt="Join our Discord server!">
  </a>
  <a href="https://docs.lavague.ai/en/latest/"><img src="https://img.shields.io/badge/docs-000000?style=for-the-badge&colorB=07f" height='35px' alt="Docs"></a>
</h4>
  <p>Copilot for devs to automate automation</p>
<h1></h1>
</div>

## 🏄‍♀️  What is LaVague?

LaVague is an **open-source** project designed to automate automation for devs! 

We use **advanced AI techniques** (RAG, Few-shot learning, Chain of Thought) to turn **natural language instructions** into Python code leveraging **Selenium**. LaVague is designed to make it easy for users to **automate web workflows** and execute them on a browser.

### LaVague in Action

Here's an example to show how LaVague can execute natural language instructions on a browser to automate interactions with a website:

<div>
  <figure>
    <img src="static/hf_lavague.gif" alt="LaVague Interaction Example" style="margin-right: 20px;">
    <figcaption><b>LaVague interacting with Hugging Face's website.</b></figcaption>
  </figure>
  <br><br>
</div>

## 🚀 Getting Started

### Running LaVague in your local env

You can get started with `LaVague` in 2 steps:

1. Install LaVague & dependencies
```
wget https://raw.githubusercontent.com/lavague-ai/LaVague/main/setup.sh &&
sudo bash setup.sh
```

2. Run your LaVague command!

You can either `launch` an interactive demo, where LaVague will execute and show you the results of the automation code it generates for your instruction.
```
lavague --instructions examples/instructions/huggingface.yaml --config examples/configurations/api/openai_api.py launch
```

Or you can use the `build` command to directly get the Python code leveraging Selenium in a file, which you can then inspect & execute locally.
```
lavague --instructions examples/instructions/huggingface.yaml --config examples/configurations/api/openai_api.py build
```

For a step-by-step guide or to run LaVague in a Google Colab, see our [quick-tour](https://docs.lavague.ai/en/latest/docs/get-started/quick-tour/) which will walk you through how to get set-up and launch LaVague with our CLI tool.

## 🎭 Playwright integration

If you want to get started with LaVague build using Playwright as your underlying automation tool, see our [Playwright integration guide](./docs/docs/get-started/playwright.md)

## 🙋 Contributing

We would love your help in making La Vague a reality. 

To avoid having multiple people working on the same things & being unable to merge your work, we have outlined the following contribution process:

1) 📢 We outline tasks on our [`backlog`](https://github.com/orgs/lavague-ai/projects/1/views/3): we recommend you check out issues with the [`help-wanted`](https://github.com/lavague-ai/LaVague/labels/help%20wanted) labels & [`good first issue`](https://github.com/lavague-ai/LaVague/labels/good%20first%20issue) labels
2) 🙋‍♀️ If you are interested in working on one of these tasks, comment on the issue! 
3) 🤝 We will discuss with you and assign you the task with a [`community assigned`](https://github.com/lavague-ai/LaVague/labels/community-assigned) label 
4) 💬 We will then be available to discuss this task with you
5) ⬆️ You should submit your work as a PR
6) ✅ We will review & merge your code or request changes/give feedback

Please check out our [`contributing guide`](./contributing.md) for a more detailed guide.

If you want to ask questions, contribute, or have proposals, please come on our [`Discord`](https://discord.gg/SDxn9KpqX9) to chat!

## 🗺️ Roadmap

TO keep up to date with our project backlog [here](https://github.com/orgs/lavague-ai/projects/1/views/2).

### 🚨 Disclaimer

This project executes LLM-generated code using `exec`. This is not considered a safe practice. We therefore recommend taking extra care when using LaVague (such as running LaVague in a sandboxed environment)!
