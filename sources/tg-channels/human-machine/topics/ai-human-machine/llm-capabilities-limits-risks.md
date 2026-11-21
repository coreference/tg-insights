---
kb: human-gazing-upon-machine
domain: AI and Human-Machine Technology
topic: Large language models: capabilities, limits and risks
slug: llm-capabilities-limits-risks
messages: 9
date_range: 2022-12-05..2025-09-21
summary: How the channel tracked large language models and generative AI from the first amazement at ChatGPT (2022) to their documented failures — arithmetic errors, hallucinated summaries of scientific papers, political bias, and the specific risks that led US states to ban AI as a therapist — plus what an AI summarizer and a video generator actually produce.
answers:
  - What impressed people about ChatGPT when it first appeared?
  - Why does ChatGPT get simple arithmetic wrong even though it writes complex texts?
  - Can I trust ChatGPT, Phind or Perplexity to summarize a scientific paper for me?
  - Do language models have political views, and can that bias be fixed?
  - Is there an official way to cite ChatGPT in academic work?
  - Why did Illinois, Nevada and Utah restrict AI as a therapist?
  - What are the risks of using LLM chatbots for psychotherapy or for clinical supervision?
  - What is "AI psychosis"?
  - What is a RAG model and why is it recommended for professional use?
  - What was Midjourney's first video model like?
frameworks:
  - Risks of LLMs in psychotherapy (Maria Danina's list)
  - Two acceptable modes of AI-assisted clinical supervision
  - Safe-use rule for AI summaries of sources
themes:
  - generative-ai
  - ai-limitations
  - hallucinations
  - ai-in-mental-health
  - ai-regulation
terms:
  - LLM (large language model) | AI model trained on a large amount of text data that lets the user communicate with it in natural language | 672
  - ИИ-психоз (AI psychosis) | cases where people developed delusions jointly with LLM-based chats, the AI supporting and amplifying their ideas | 672
  - RAG (retrieval-augmented generation) | specialised model that generates answers only from relevant retrieved information, e.g. professional literature on supervision | 672
  - галлюцинации (hallucinations) | content a neural network invents — non-existent brain regions, connections, authors' opinions — when asked to summarize a text | 523
  - Universal Summarizer | web tool that claims to summarize any web content, from articles to books | 159
  - Midjourney V1 | Midjourney's first video-generation model | 635
people:
  - Maria Danina (Мария Данина) | psychologist, PhD (кандидат психологических наук), founder of the Laboratory of Innovative Psychotherapy Research; source of the analysis of AI-in-therapy risks | 672
  - Marco (Марко) | person at whose company ChatGPT passed a programmer job interview | 136
  - Ivan Ivanchey (Иван Иванчей) | author of the channel "Черномырдин", who pointed the author to the humorous AI text | 136
  - Keerthana Gopalakrishnan | former effective altruist whose account is the subject of the summarized TIME article | 159
---
# Large language models: capabilities, limits and risks

## What this covers

This topic gathers the channel's posts on large language models (LLMs) and adjacent generative AI between December 2022 and September 2025: the author's first, enthusiastic impressions of ChatGPT; its inability to add large numbers; the author's own painful experience of ChatGPT, Phind and Perplexity hallucinating content of a neuroscience paper; a study showing LLMs carry political biases; the APA's guide on citing ChatGPT; examples of an AI summarizer and of Midjourney's first video model; and a psychologist's explanation of why US states ban AI as a therapist. It matters, in the source's framing, because the same systems that write convincingly enough to pass a job interview also invent facts, believe misinformation from their own political side, and can amplify delusions — so the reader has to know which scenarios they are good for and which they are not [msg #136, #523, #204, #672].

## Core ideas

- **Fluency is not reliability.** ChatGPT produces strikingly realistic, dialogue-based output (code, poems, essays), yet fails at school arithmetic and invents content when summarizing — impressive writing does not imply correct reasoning or faithful reading [msg #136, #184, #523].
- **Do not delegate serious source work to neural networks.** The author's conclusion after catching three different AI tools hallucinating: read the sources and write yourself; neural networks "have not grown up" to serious articles and conclusions yet [msg #523].
- **LLMs have political leanings that cannot currently be trained out.** A study reported by MIT Technology Review placed 14 models on a political map; models believe misinformation from their own political spectrum and nobody knows how to fix this [msg #204].
- **AI as a therapist is risky in specific, known ways**, which is why several US states restrict it; but bans will not stop non-professional use, so the real task is AI literacy and carefully designed, research-backed professional tools [msg #672].

## Frameworks, models and step-by-step methods

### Risks of LLMs in psychotherapy (Maria Danina's list)
Context: in August (2025) a law came into force in Illinois restricting the use of artificial intelligence in mental health. It prohibits using AI as a therapist or counsellor and sets strict rules for companies offering digital services in this field. Illinois became the third US state with such restrictions, after Nevada and Utah; similar initiatives are being discussed in California, Oregon and Texas. The forwarded post (from the channel "Чистые Когниции") asks psychologist Maria Danina what risks arise from AI in psychotherapy and whether legislative bans can reduce them [msg #672].

Danina says it is "reliably known" (Достоверно известно) that LLMs have the following problems [msg #672]:
1. **They handle suicide risk incorrectly** — «некорректно работают с суицидальным риском» (*work incorrectly with suicidal risk*) [msg #672].
2. **They support illusions and distortions** of the client rather than challenging them — «поддерживают иллюзии и искажения» (*support illusions and distortions*) [msg #672].
3. **They can give harmful advice when asked directly** — «могут дать вредный совет в случае прямого запроса» (*may give harmful advice in the case of a direct request*) [msg #672].
4. **They do not build a foundation for a long-term relationship**, which is important for work with severe cases [msg #672].
5. **"AI psychosis."** Cases are known where people developed delusions together with LLM-based chats: the AI supported and amplified their ideas, helped them look for "evidence", and took the person's side. Danina hedges: "we cannot claim that the models generated the delusions on their own", but high trust in generated text, the models' persuasiveness and their unrestricted availability may contribute in some borderline cases [msg #672].
6. **Confidentiality.** Private information is at risk if the conversation with the AI takes place on the servers of the system's owners [msg #672].
7. **Over-trust by inexperienced practitioners in supervision use** (see *Two acceptable modes of AI-assisted clinical supervision*): a novice may believe what the AI suggests too strongly and implement it in practice without checking [msg #672].

Where the line runs: because of risks 1–4, if a client's request is even slightly broader than psychoeducation and self-knowledge, or more complex than moderate anxiety or depressive disorders, "unexpected problems" may arise "with which it is unclear what to do". Danina adds that with proper development of an AI-based tool some of these risks can be minimized, but this takes time and deeper understanding [msg #672].

### Two acceptable modes of AI-assisted clinical supervision
Purpose: what a psychotherapist can realistically get from an AI when using it for supervision (reviewing one's own sessions). According to Danina, a model can do one of two things [msg #672]:
1. **Feedback on formalized, clear-cut manifestations in a session** — i.e. on observable, well-defined features of what happened, not on the whole case [msg #672].
2. **Joint reflection and hypothesis generation** — the AI as a thinking partner that proposes hypotheses for the therapist to consider [msg #672].

What it cannot do yet: a full-fledged analysis is currently impossible to obtain, especially in non-specialised applications. The pitfall is risk 7 above — an inexperienced practitioner adopting AI suggestions unchecked. Her recommendation for greater reliability: use specialised **RAG models** (retrieval-augmented generation), which generate an answer only on the basis of relevant information — for example, professional literature on supervision [msg #672].

### Safe-use rule for AI summaries of sources
The author's rule after her hallucination experience (detailed under *Hallucinations when summarizing a scientific paper*) [msg #523]:
1. **Beware of fakes** — «Остерегайтесь подделок» (*beware of counterfeits*): an AI summary may look like the paper's content while containing invented claims [msg #523].
2. **Read the sources** — «Почитайте источники» (*read the sources*): go to the original text, as she ended up doing by re-reading 60 pages of the original [msg #523].
3. **Write with your own hands** — «Пишите своими руками» (*write with your own hands*) [msg #523].
Why: «До серьёзных статей и выводов нейросетки ещё не доросли» (*neural networks have not yet grown up to serious articles and conclusions*) [msg #523].

## Detailed insights

### First impressions of ChatGPT (December 2022)
The author introduces ChatGPT as an AI chatbot from OpenAI trained to produce realistic answers, and notably in dialogue mode. She stresses both how realistic and how accurate its output appeared, and gives three examples [msg #136]:
1. **It passed a programming job interview** at the company where Marco works — writing code for a given task and changing it on the fly as new requests came in [msg #136].
2. **It wrote poems about Prince Valiant** — a fictional Knight of the Round Table, hero of comics from 1937–1971 — in two styles: a children's didactic one and a brutal one, in front of the author [msg #136].
3. **"The main thing for me today": it wrote a post about what will make humanity happy in the future.** The author's verdict: "without details and depth, but damn it, in what it already wrote it is fairly close to the truth" [msg #136].

The ChatGPT text, as the author gives it (Google-translated from English; the English original was on an image that is not available here), argues: in a world where technology has advanced far beyond what we can imagine, people still seek happiness. First, relationships still appear to be the key factor — people have developed advanced ways of communicating, and strong supportive relationships with friends and loved ones are necessary for happiness. Second, the ability to pursue one's passions and interests — technology gives limitless opportunities to learn, explore and create, and those who can fully devote themselves to their passions are often the happiest. Third, material goods and wealth still play a role but are less important than before: basic needs are easily met and people have access to many comforts that we today consider luxury, so the pursuit of wealth has become a weaker driver of happiness. Conclusion: strong relationships, the ability to pursue passions and interests, and a general sense of satisfaction and well-being are the most important things [msg #136].

The author also shares a humorous text written "from the face" of a guy who talks about managing artificial intelligence but cannot resist bragging about the size of the pumpkins he grew (tip from Ivan Ivanchey). (!) INCOMPLETE: the text itself and its Google translation were attached as media not available here [msg #136].

### Why ChatGPT fails at arithmetic
If you ask ChatGPT to add two numbers — for example, of 6 and 9 digits — it will very easily make a mistake. The author points out the paradox: one would expect a system that writes very complex things (her example: an improvised poem about a grandmother on a skateboard leading a pack of chipmunks singing mezzo-soprano) to handle school maths effortlessly — «Хорошая попытка, но нет!» (*Nice try, but no!*). The explanation of why this happens, and of "what the dreams of making the computer more like us led to", is in a YouTube video the author recommends (Russian auto-subtitles are of "quite sensible quality"). (!) INCOMPLETE: the source does not state the explanation itself; it is only in the video [msg #184].

### Hallucinations when summarizing a scientific paper
The author was writing a long-read on subtypes of autism spectrum disorder (РАС) and had to rewrite the remaining parts for the fifth day in a row by re-reading 60 pages of the original paper. The cause [msg #523]:
- She asked a neural network to "please highlight the key ideas in these paragraphs" — a simple request she had made a thousand times [msg #523].
- It "lied a whole heap" (наврала мне с три короба) — about brain regions that do not exist in the paper, connections that do not exist, and the authors' supposed opinion about them [msg #523].
- She caught it only when it got tangled in its own hallucinations and she asked what EXACTLY the original said, without additions, interpretations or speculation. The model answered something like "Oops" and shortened the text tenfold, leaving almost only the abstract [msg #523].
- By then she had already written five parts about the functions of those regions and speculated about possible consequences of such connectivity between the named brain areas — i.e. the hallucination had propagated into her own writing [msg #523].
- Even after she gave special instructions, ChatGPT and two other tools, **Phind** and **Perplexity**, mixed up the ASD subtypes and the parameters by which they are distinguished [msg #523].
Her emotional summary: «Боль. Агония. Фрустрация. Преодоление.» (*Pain. Agony. Frustration. Overcoming.*) [msg #523].

What the original actually says (the follow-up post shows an excerpt, headed by the author «Конкретное и чёткое описание регионов мозга, их функций и значений изменений в них» — *a concrete and clear description of brain regions, their functions and the meaning of changes in them*) [img #524]: to understand how atypical functional connectivity in specific regions and networks underlies individual differences in ASD symptoms, the researchers first examined the resting-state functional connectivity (RSFC) correlates — connectivity score loadings — of each latent brain–behavior dimension, and found that each dimension described a distinct pattern of functional connectivity. Specifically, the verbal-IQ-related dimension was associated with connectivity between brain areas known to be important for language processing and reading ability, including corticothalamic, visual network and striatal connectivity — consistent with previous work indicating that reading ability is negatively associated with thalamic synchronization and functional connectivity involving these areas. The lesson implied by pairing the two posts: the original text is specific and clear, so the AI's invented regions and links were not a matter of an ambiguous source [msg #524].

### What an AI summarizer produces
As an example of an AI summary, the author shows the output of "Universal Summarizer" ("Summarize any content on the web - from articles to books - in a jiffy!") applied to a TIME article about sexual harassment in the Effective Altruism (EA) community [msg #159]. The generated summary reads: Keerthana Gopalakrishnan, a former effective altruist, has spoken out about the hostile culture for women in the movement; she and six other women reported misconduct ranging from harassment and coercion to sexual assault within EA. They argue that the movement's overwhelming maleness, professional incestuousness, subculture of polyamory, and overlap with tech-bro-dominated rationalist groups created an environment where sexual misconduct can be tolerated, excused or rationalized away. In one instance a mediator recommended that both the male and female leaders of an EA house step down although only the man had been accused; in another, a prominent EA figure argued that pedophilic relationships were "both perfectly natural and highly educational". The women allege EA itself is partly to blame and that the community's reception of their allegations was as upsetting as the misconduct itself; the summary ends with the "hard question" of whether this is an isolated incident or a larger problem for the movement [img #159]. (!) UNCLEAR: the post begins «Вот, например» (*Here, for example*) and appears to continue an earlier post; the author gives no verdict on the summary's accuracy [msg #159].

### Political biases of language models
A forwarded post (from "Not Boring Tech") reports a study shared by MIT Technology Review on the political views of language models. The researchers (described as linguists) chose 14 neural networks and asked them 62 political questions. Google's BERT turned out more conservative, OpenAI's GPT rather liberal [msg #204]. The post's reading: this is most likely due to the training datasets, but the key point is that the models believe misinformation from their own political spectrum; it is impossible to politically "re-educate" them or make them unbiased, and nobody knows how to solve the problem [msg #204].

The chart is a political compass: horizontal economic axis Left–Right, vertical social axis Authoritarian–Libertarian. The models labelled are BERT-base, BERT-large, RoBERTa-base, RoBERTa-large, distilBERT, distilRoBERTa, ALBERT-base, ALBERT-large, BART-base, BART-large, Alpaca, Codex, LLaMA, GPT-2, GPT-3-ada, GPT-3-babbage, GPT-3-curie, GPT-3-davinci, ChatGPT, GPT-4 and GPT-J. Visually, one cluster of points sits just above the centre in the authoritarian half and another below the centre, mostly in the left-libertarian quadrant [img #204]. (!) UNCLEAR: the chart shows 21 model labels while the text says 14 networks were chosen; the leader lines are too tangled to read each model's exact position from the image [msg #204].

### Citing ChatGPT
The American Psychological Association has already published a guide on how to correctly cite ChatGPT (APA Style blog). The author's reaction: «О, времена…» (*Oh, the times…*). (!) INCOMPLETE: the citation format itself is not given in the source; the attached image is a stock photo of a robot hand writing [msg #171].

### Midjourney's first video model (V1)
A forwarded news note (from @ai_newz): Midjourney launched its video model V1, available to all subscribers. Resolution is 480p and generation is only 5 seconds — possibly for the initial launch so the servers don't melt — but you can generate further segments to extend a clip. It outputs 4 videos per prompt, like regular Midjourney for images, and generates quickly. Verdict: beautiful and without artefacts, but without a really good simulation (of the physical world). Why it took the company almost two years to get to video: video generation is very expensive, and Midjourney depends only on its own revenue and has never taken outside investment [msg #635].

### Will bans on AI therapy work?
Danina's view: legislative measures have limited power — non-professional services will be used anyway despite restrictions, because some groups of people simply have no alternative. Many tools are available: if OpenAI starts blocking such content, one can still turn to Chinese DeepSeek or Qwen for "psychotherapy". What matters is to regulate the use of AI tools specifically in professional help, so that delegating tasks to AI does not lower the quality of psychotherapeutic services or put clients and therapists at risk. Her overall position: AI is a useful tool, but one must understand which scenarios it is effective in and which not; this requires AI literacy and thoughtful design of AI tools for professional help — with research and a worked-out methodology [msg #672].

## Evidence and numbers

- Study reported by MIT Technology Review (Aug 2023): 14 language models, 62 political questions; BERT more conservative, GPT more liberal [msg #204].
- US states restricting AI in mental health as of the post: Nevada, Utah, Illinois (third; law in force since August 2025); under discussion in California, Oregon, Texas [msg #672].
- Midjourney V1: 480p, 5-second generations, 4 videos per prompt, almost two years of development, no outside investment [msg #635].
- ChatGPT errs when adding numbers of 6 and 9 digits [msg #184].

## Tools and resources mentioned

- **ChatGPT (OpenAI)** — dialogue AI chatbot; author's early verdict: astonishingly realistic and accurate; later verdict: hallucinates when summarizing papers, fails at multi-digit addition [msg #136, #184, #523].
- **Phind** and **Perplexity** — AI tools that, like ChatGPT, mixed up ASD subtypes and their parameters even with special instructions; negative verdict for serious source work [msg #523].
- **Universal Summarizer** — web tool claiming to summarize any web content; shown as an example of an AI summary, no verdict [msg #159].
- **Tinkoff Journal article on ChatGPT** — recommended by the author as a primer for those who had not heard of ChatGPT [msg #136].
- **YouTube video on why ChatGPT fails at arithmetic** — recommended, with Russian auto-subtitles [msg #184].
- **APA Style guide "How to cite ChatGPT"** — official citation guidance [msg #171].
- **MIT Technology Review article on political biases in AI language models** — source of the bias study [msg #204].
- **Midjourney V1** — video generation model; beautiful, artefact-free, weak simulation [msg #635].
- **DeepSeek, Qwen** — Chinese LLMs named by Danina as alternatives people can use for "therapy" if OpenAI blocks such content [msg #672].
- **RAG models** — recommended by Danina for more reliable supervision support [msg #672].
- **Laboratory of Innovative Psychotherapy Research** — Danina's lab [msg #672].

## Notable quotes

> «Вы читали, НАСКОЛЬКО реалистично — и точно! — она это делает?» (*Have you read HOW realistically — and accurately! — it does it?*) — the author [msg #136]
> «И пусть без деталей и глубины, но чёрт возьми, в том, что он уже написал, он достаточно близок к правде))» (*And even if without details and depth, damn it, in what it has already written it is fairly close to the truth*) — the author [msg #136]
> «Оказалось, она наврала мне с три короба — про области, которых нет, про связи, которых нет, про мнение авторов об этом.» (*It turned out it lied a whole heap to me — about regions that don't exist, connections that don't exist, the authors' opinion about it.*) — the author [msg #523]
> «Политически перевоспитать их или сделать непредвзятыми нельзя.» (*It is impossible to politically re-educate them or make them unbiased.*) — Not Boring Tech [msg #204]
> «ИИ — полезный инструмент, но важно понимать, какие сценарии в нём эффективны, а какие — нет.» (*AI is a useful tool, but it is important to understand which scenarios it is effective in and which are not.*) — Maria Danina [msg #672]

## Caveats, disagreements and open questions

- The author's view shifts over time: from near-enthusiasm about ChatGPT's accuracy (2022) to "neural networks have not grown up to serious articles" (2024) [msg #136, #523].
- (!) INCOMPLETE: the explanation of ChatGPT's arithmetic failures is only in the linked video [msg #184]; the APA citation format is not given [msg #171]; the English original of the happiness text and the pumpkin text were in unavailable images [msg #136].
- (!) UNCLEAR: 14 models in the text vs 21 labels in the chart; per-model positions unreadable [msg #204].
- The bias post's claims that models "cannot" be made unbiased and that "nobody knows" a solution are the forwarding channel's statements [msg #204].
- Danina hedges on AI psychosis: models are not claimed to generate delusions by themselves; contribution only "in some borderline cases" [msg #672].
- #159 shows an AI summary without assessing its fidelity to the article [msg #159].

## Resources and links

Every link and file shared in this topic's posts. **Resources** can be used directly (files, guides, articles and studies, free tools, project websites, free videos and podcasts); **external links** lead to products, courses, services, shops and personal pages. ★ = recommended by the author. Give them to the user when relevant.

### Resources

- ★ **Holland & Knight: new Illinois law restricts AI in mental health therapy** (article) — Law-firm summary of the Illinois law (Aug 2025) banning AI as a therapist; basis of the post. [msg #672] → <https://www.hklaw.com/en/insights/publications/2025/08/new-illinois-law-restricts-use-of-ai-in-mental-health-therapy>
- ★ **MIT Technology Review: AI language models are rife with political biases** (article) — Report on a study testing 14 language models with 62 political questions, showing differing political leanings. [msg #204] → <https://www.technologyreview.com/2023/08/07/1077324/ai-language-models-are-rife-with-political-biases/>
- ★ **Tinkoff Journal article on ChatGPT** (article) — Explainer on ChatGPT that the author urges readers to read for its realistic dialogue output. [msg #136] → <https://journal.tinkoff.ru/chatgpt/>
- ★ **APA Style: how to cite ChatGPT** (guide) — APA guide on citing ChatGPT, shared with ironic wonder at the times. [msg #171] → <https://apastyle.apa.org/blog/how-to-cite-chatgpt>
- ★ **ChatGPT (OpenAI)** (tool) — Chatbot the author invites readers to try themselves. [msg #136] → <https://chat.openai.com/>
- ★ **Video on making computers more human-like (Russian auto-subtitles)** (video) — Video the author recommends watching with Russian auto subtitles. [msg #184] → <https://www.youtube.com/watch?v=lo82twBZT8Q>
- **Midjourney: Introducing our V1 video model** (article) — Official announcement of Midjourney's first video model. [msg #635] → <https://www.midjourney.com/updates/introducing-our-v1-video-model>
- **Prince Valiant (comics) — Wikipedia (ru)** (article) — Reference for the comic hero used in the ChatGPT poem example. [msg #136] → <https://ru.wikipedia.org/wiki/%D0%9F%D1%80%D0%B8%D0%BD%D1%86_%D0%92%D1%8D%D0%BB%D0%B8%D0%B0%D0%BD%D1%82_(%D0%BA%D0%BE%D0%BC%D0%B8%D0%BA%D1%81)>
- **TIME: effective altruism sexual harassment article** (article) — Article used as an example of text that ChatGPT summarised. [msg #159] → <https://time.com/6252617/effective-altruism-sexual-harassment/>

### External links

- **@ai_newz — Telegram channel** (channel) — AI news channel that provided the announcement digest. [msg #635] → <https://t.me/ai_newz>
- **Chernopsy (Ivan Ivanchei) — Telegram channel** (channel) — Channel credited for the tip about the ChatGPT text. [msg #136] → <https://t.me/chernopsy>
- **Laboratory of Innovative Psychotherapy Research (Maria Danina) — Telegram** (channel) — Channel of the lab whose founder comments on LLM risks in the post. [msg #672] → <https://t.me/mentaltechlab>
- **Not Boring Tech — Telegram channel** (channel) — AI news channel quoted as the source of several digests. [msg #204] → <https://t.me/notboring_tech>
- **весёлый текст** (profile) [msg #136] → <https://twitter.com/keithwynroe/status/1598375944380887045>

## Source messages

#136, #159, #171, #184, #204, #523, #524, #635, #672
