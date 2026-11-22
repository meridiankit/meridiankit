<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=1B3A4B&height=190&section=header&text=MeridianKit&fontSize=46&fontColor=ffffff&fontAlignY=40&desc=Data%20%C2%B7%20agents%20%C2%B7%20software&descAlignY=64&descSize=18&descFontColor=D6E2EA" width="100%" alt="MeridianKit" />

<img src="https://readme-typing-svg.demolab.com?font=Source+Sans+3&weight=500&size=22&duration=2800&pause=900&color=1B3A4B&center=true&vCenter=true&width=720&lines=Tools+for+data%2C+agents%2C+and+software;Open+source+here.+A+hosted+run+when+it+earns+one.;One+tool.+One+job.+A+sample+of+the+output." alt="Tools for data, agents, and software" />

<br/>

<img src="https://img.shields.io/badge/Python-1B3A4B?style=flat-square&logo=python&logoColor=white" alt="Python" />
<img src="https://img.shields.io/badge/MCP-1B3A4B?style=flat-square" alt="MCP" />
<img src="https://img.shields.io/badge/Apify-1B3A4B?style=flat-square" alt="Apify" />
<img src="https://img.shields.io/badge/Docker-1B3A4B?style=flat-square&logo=docker&logoColor=white" alt="Docker" />

<br/><br/>

<img src="https://komarev.com/ghpvc/?username=meridiankit&style=flat-square&color=1B3A4B&label=visitors" alt="Profile visitors" />

</div>

<br/>

MeridianKit builds small tools that do one job. A tool pulls a public dataset, gives an agent a single capability, or runs a workflow on a schedule.

The source lives in this account. When a hosted run exists, that tool's README links to it.

## Start here

| I want to… | Where it lives |
| --- | --- |
| Pull a public dataset | A repository here, and an Apify Actor when it should run on a schedule |
| Give an agent one job | An MCP server or a skill in its own repository |
| See what a tool returns | The sample in that repository's README |

Tools are added one repository at a time. Nothing is listed here until it actually runs.

## How a tool is shipped

```mermaid
flowchart LR
  source[Source in this account]
  sample[Sample output in the README]
  hosted[Hosted run, when it earns one]
  source --> sample --> hosted
```

| Piece | What you get |
| --- | --- |
| `README.md` | What it does, one sample, and the hosted link when there is one |
| `src/` | The tool |
| `examples/` | One input and the output it produces |

## Stack

Python for the tools. MCP when an agent needs to call one. Apify when the job should run on a schedule. Docker when the tool needs a fixed environment.

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=1B3A4B&height=110&section=footer" width="100%" alt="" />

</div>
