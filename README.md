<div align="center">
    <img src="background.png" alt=""/>
</div>

# SkyAGI: an End to End Application based on Generative Agents
<p align="center">
    <a href="https://pypi.org/project/skyagi/">
        <img alt="PyPI" src="https://img.shields.io/pypi/v/skyagi?color=gree">
    </a>
</p>

`SkyAGI` is a python package that demonstrates LLM's emerging capability in simulating believable human behaviors.
Specifically, `SkyAGI` implements the idea of [Generative Agents](https://arxiv.org/abs/2304.03442) and delivers a role-playing game that creates a very interesting user experience.

Different from previous AI based NPC systems, `SkyAGI`'s NPC generates very interesting response and believable human behaviors.
The interesting observations in this demo show a huge potential for rethinking game development in many aspects. NPCs can take different actions based on the conversation between players and other NPCs, they can also influence each other's memories and actions through conversation, allowing game designers to create a more personalized experience. A more intriguing aspect is that each NPC has its own mindset and routine, and they also have social relationships with each other. This increases the complexity of the social network and provides an exponential growth of content for players to consume. Combining this with interesting gameplay could potentially introduce a new and exciting gaming experience.

To demonstrate this, `SkyAGI` provides example characters from `The Big Bang Theory` and `The Avengers` as a starting point.
For more details about the observations, refer to the [observations section](https://github.com/litanlitudan/skyagi/#interesting-observations-in-this-demo)

## Quick Start

Installation

```sh
pip install --upgrade skyagi
```

How to run

```sh
export OPENAI_API_KEY="..."
skyagi
# or
OPENAI_API_KEY="..." skyagi
```

For example if the OpenAI key is `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`, then the exact command would be the following

```sh
# make sure no quote around the token
export OPENAI_API_KEY=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
skyagi
# or
OPENAI_KEY_KEY=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 skyagi
```

## Interesting observations in this demo

## References

1. https://arxiv.org/abs/2304.03442
2. https://python.langchain.com/en/latest/use_cases/agent_simulations/characters.html#create-a-generative-character
