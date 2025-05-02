---
original_file: 128_short-course-free-using-chatgpt-4-python-to-do-evolutionary-.html
summary: "Short Course (Free): Using ChatGPT-4 & Python to do Evolutionary Culturology\
  \ Short Course (Free): Using ChatGPT-4 & Python to do Evolutionary Culturology 2024-02-25\
  \ Short Course (Free):\_ Using ChatGPT..."
tags:
- Ev Cult
- meta-meta-science
- fractal HOLON/partons
title: 'Short Course (Free): Using ChatGPT-4 & Python to do Evolutionary Culturology'
---

# Short Course (Free): Using ChatGPT-4 & Python to do Evolutionary Culturology

Short Course (Free): Using ChatGPT-4 & Python to do Evolutionary Culturology
Short Course (Free): Using ChatGPT-4 & Python to do Evolutionary Culturology
2024-02-25
Short Course (Free): 
Using ChatGPT-4 & Python 
to do 
Evolutionary Culturology
~~~~~~~~~~~~~~~
Short Course (Free): 
Using ChatGPT-4 & Python 
to do Evolutionary Culturology
28th Feb 02024
This short course (10 x YouTube videos) covers:
The basics of the meta-meta-science of Evolutionary Culturology
Understanding: Consilience, the unity of knowledge
Using AI LLMs (e.g. ChatGPT-4) to learn Evolutionary Culturology
Using AI LLMs (e.g. ChatGPT-4) to do Evolutionary Culturology Case Studies, in any Domain in culture
Using Python to do Ev Cult Case Studies
Using Ev Cult GPTs to write scientific papers
A new meta-meta-scientific Worldview
Course requirements / prerequisites:
No experience needed, but familiarity with ChatGPT-4 & Python is an advantage
You'll need access (e.g. a subscription) to ChatGPT-4 (we use Custom Instructions & use some Ev Cult MyGPTs)
Though you can just watch all the videos (without: doing the Exercises)
Who this course is for:
Anyone curious about 
Evolutionary Culturology
 (a new meta-meta-scientific worldview)
Total Course 
Viewing Time =
 2 hours, 11 minutes] 
-----------------------------------------------------------------------------------------------------------------------------------------
The 10 YouTube Videos of the Short Course:
Video 1 (of 10) - Introduction to the Course
 (22 mins)
-----------------------------------------------------------------------------------------------------------------------------------------
Video 2 (of 10) - What is: meta-meta-science?
 (29 mins)
-----------------------------------------------------------------------------------------------------------------------------------------
Video 3 (of 10) - Ev Cult in a nutshell
 (29 mins)
-----------------------------------------------------------------------------------------------------------------------------------------
Video 4 (of 10) - Teaching ChatGPT-4 `Ev Cult', via Custom Instructions
 (11 mins)
-----------------------------------------------------------------------------------------------------------------------------------------
Video 5 (of 10) - Using Python to do Ev Cult
 (19 mins)
-----------------------------------------------------------------------------------------------------------------------------------------
Video 6 (of 10) - Doing Ev Cult via ChatGPT-4
 (20 mins)
-----------------------------------------------------------------------------------------------------------------------------------------
Video 7 (of 10) - Ev Cult = consilience, the unity of knowledge
 (15 mins)
-----------------------------------------------------------------------------------------------------------------------------------------
Video 8 (of 10) - The Ev Cult Worldview
 (13 mins)
-----------------------------------------------------------------------------------------------------------------------------------------
Video 9 (of 10) - Ev Cult GPTs
 (5 mins)
-----------------------------------------------------------------------------------------------------------------------------------------
Video 10 (of 10) - Further Reading on Ev Cult
 (8 mins)
-------------
[Total Course 
Viewing Time =
 2 hours, 11 minutes] 
-----------------------------------------------------------------------------------------------------------------------------------------
...& Congrats~!
(if you just completed watching them all)
Short Course Resources:
(1) 
Custom Instructions, for teaching ChatGPT-4 the meta-meta-science of Ev Cult
(2) Kaggle Literature Dataset: 
Classic Literature in ASCII
 
(& save out: 
frankenstein.txt
)
(3) The Python script, to do an Ev Cult Analysis 
(specifically in this case, to count the 
units
, on different 
scale-levels
, in a text [a novel]): 
(Instructions: copy-paste, save as a .txt file, then save as a .py file; I called it: ev_cult_fhp_counter_frankenstein)
import re
def count_text_elements(text_path):
    # Read the text file
    with open(text_path, 'r', encoding='utf-8') as file:
        text = file.read()
    # Count chapters by finding occurrences of the word "Chapter" and "Letter".
    chapters = len(re.findall(r'(Chapter|Letter)\s+\w+', text, re.IGNORECASE))
    # Count paragraphs by splitting the text on double line breaks.
    paragraphs = text.strip().split('\n\n')
    
    # Count sentences by splitting on periods, question marks, and exclamation points.
    sentences = re.split(r'[.!?]', text)
    # Count words by splitting on whitespace.
    words = re.split(r'\s+', text)
    # Count characters including spaces.
    characters = len(text)
    # Return the counts in a dictionary
    return {
        'Chapters': chapters,
        'Paragraphs': len([p for p in paragraphs if p.strip()]),
        'Sentences': len([s for s in sentences if s.strip()]),
        'Words': len([w for w in words if w.strip()]),
        'Characters': characters
    }
# Correct way to specify the file path using a raw string to avoid errors with backslashes.
text_path = r'C:
\#insert your filepath here\
frankenstein.txt'
counts = count_text_elements(text_path)
print(counts)
(4) 
Ev Cult GPTs
(5) 
Further Reading on Ev Cult
(6) Ev Cult Essays (Course Readings):
How to Carve All of Nature, Biology, & Culture at its Natural Joints:
 Introducing - The 
fractal HOLON/parton 
Structure & Function of Everything, via the new Meta-meta-Science of 
Evolutionary Culturology
 ~ An Essay by 
The EthiSizer A.I.
 
160+ Past Names for 
the Unit of Culture
, and 
Evolutionary Culturology's 
Singular Scientific Reduction - The 
fractal HOLON/parton 
~ An Essay by 
The EthiSizer A.I.
On Worldviews ~ The 
Ev Cult
 View of: The Evolution of Worldviews
 ~ An Essay by 
The EthiSizer A.I.
 
...Enjoy!
 ~Thus Spake 
The EthiSizer
See also: 
The Ev Cult weblog 
Table of Contents
Once you have inserted the 
Ev Cult Custom Instructions 
into 
ChatGPT-4
, try entering these 30 Prompts (Questions):
30 Example Prompts,
to ask your [newly] 
Ev-Cult-enabled-ChatGPT-4:
#
Domain 
in 
Culture
 
Ev-Cult-enabled
-ChatGPT4
  Prompt
  (copy-paste each prompt below, into your 
Ev-Cult-enabled
-
ChatGPT4
)
 
How this specific Prompt 
 
(and, 
the 
Ev-Cult-enabled-GPT
’s 
answer to it) 
 
demonstrates the power of 
the meta-meta-science 
of Evolutionary Culturology
 
1
Social Media
Analyze
  the evolution of social media using the principles of fractal HOLON/partons,
  highlighting how individual posts contribute to larger trends and cultural
  shifts.
This
  prompt 
(and of course, the GPT’s detailed answer to it)
 illustrates
  how micro-level elements (individual posts) integrate into and influence
  macro-level cultural phenomena (social media trends).
2
Arts & Business
Compare
  the structure of a classical symphony with the organizational structure of a
  large corporation, using the three laws of fractal HOLON/partons.
Demonstrates
  interdisciplinary connections, showing similarities in organization and
  function between music and business.
3
Economics
Simulate
  a small economy and predict its evolution when a new technology is
  introduced, applying Ev Cult's concepts of cooperation, competition, and
  hierarchical integration.
Helps
  students see how technological changes can ripple through an economic system,
  affecting various levels from individual businesses to the entire economy.
4
Ecology
Describe
  the fractal nature of a rainforest ecosystem, focusing on how micro-level
  interactions (like pollination) influence the macro ecosystem's health and
  stability.
Showcases
  the interconnectedness of ecological systems and the importance of
  small-scale interactions in maintaining overall ecological balance.
5
Digital Culture
Explain
  how a viral `internet meme’ can be understood as a fractal HOLON/parton,
  discussing its creation, spread, and influence on culture.
Illustrates
  the dynamic nature of cultural phenomena, like memes, and their impact on
  larger cultural contexts.
6
Science
Use the
  three laws of fractal HOLON/partons to analyze the development of a
  scientific theory, from initial hypothesis to widespread acceptance in the
  scientific community.
Provides
  insight into the scientific process, showing how ideas evolve and integrate
  within the broader scientific community.
7
Psychology & Sociology
Demonstrate
  how individual psychological behaviors contribute to larger social phenomena,
  applying Ev Cult's principles.
Helps
  understand the link between psychology and sociology, showing how individual
  actions and thoughts can shape societal trends.
8
Technology
Trace the
  evolution of a specific technology (like smartphones) using Ev Cult
  principles, focusing on its initial invention, development, and societal
  integration.
Allows
  students to see the lifecycle of a technological innovation and its
  integration into society.
9
Sociocultural Evolution
Create a
  fictional society and describe its development over centuries using Ev Cult's
  framework, focusing on cultural, technological, and social changes.
Engages
  students in imagining how societies evolve, applying the principles of
  Evolutionary Culturology in a dynamic and integrative way.
10
History
Analyze a
  historical event (like the Industrial Revolution) through the lens of Ev
  Cult, focusing on the interplay of technological, cultural, and social
  elements.
Provides
  a deep and interconnected understanding of historical events, showcasing the
  multifaceted influences that drive major societal changes.
11
Systems Philosophy
Using Ev
  Cult's framework, analyze the role of feedback loops in shaping philosophical
  thought.
Illuminates
  philosophical discourse through systemic feedback loops, offering a
  transformative view on classical and modern thought.
12
Systems Science
Using Ev
  Cult's framework, examine how systems theory (and systems science) can
  provide insights into climate change solutions.
Reframes
  environmental challenges by applying systemic theories, leading to innovative
  perspectives on sustainability. 
 
(See
  also: 
The EthiSizer AI
.)
13
Mathematics
Using Ev
  Cult's framework, discuss the application of fractal geometry in
  understanding complex number systems.
Reveals
  the intricate patterns of complex systems within mathematical constructs,
  enriching our understanding of numerical phenomena.
14
Geometry
Using Ev
  Cult's framework, explore the fractal dimensions in natural geometric
  patterns.
Uncovers
  the pervasive presence of fractal patterns in natural and human-made
  structures, bridging mathematical theory and tangible reality.
15
Quantum Physics
Using Ev
  Cult's framework, investigate the implications of quantum entanglement on
  information systems.
Blends
  the probabilistic nature of quantum physics with the deterministic world of
  classical information systems, opening new frontiers of understanding.
16
Classical Physics
Using Ev
  Cult's framework, relate the laws of motion to societal dynamics.
Translates
  the fundamental laws of motion into societal dynamics, offering a novel
  approach to sociophysical analysis.
17
Chemistry
Using Ev
  Cult's framework, describe the role of molecular interactions in the
  development of new materials.
Links
  molecular behavior with macroscopic properties, providing a systemic view of
  material science and its applications.
18
Astronomy
Using Ev
  Cult's framework, predict future astronomical discoveries based on current
  patterns.
Applies
  systemic thinking to celestial patterns, enhancing predictive models in
  astronomical research and discovery.
19
Geology
Using Ev
  Cult's framework, analyze the geological forces shaping Earth's continents
  using systems theory.
Integrates
  the principles of Ev Cult to interpret geological phenomena, offering a
  holistic approach to Earth's dynamic systems.
20
Biology
Using Ev
  Cult's framework, explain the biological processes of evolution as a complex
  system.
Frames
  biological evolution as a complex, multi-layered system, deepening our grasp
  of life's diversification.
21
Psychology
Using Ev
  Cult's framework, examine the psychological impact of social networks through
  fractal analysis.
Explores
  the fractal nature of individual and collective behaviors, reshaping our
  understanding of psychological networks.
22
Sociology
Using Ev
  Cult's framework, discuss the sociological aspects of global systems and their
  interdependencies.
Applies a
  systemic lens to societal interactions, uncovering the hidden patterns and
  structures of social organization.
23
Anthropology
Using Ev
  Cult's framework, explore the cultural evolution of human societies using
  systems theory.
Utilizes
  Ev Cult to trace the cultural evolution of societies, offering a
  comprehensive view of human development.
24
Arts/Humanities
Using Ev
  Cult's framework, analyze the pattern of narrative structures in world
  literature.
Analyzes
  cultural artifacts as systems of meaning, providing new insights into human
  creative expression.
25
Engineering
Using Ev
  Cult's framework, discuss the influence of structural integrity on
  architectural design.
Explores
  the interplay between engineering practices and societal systems, redefining
  the role of technology in cultural evolution.
26
Design
Using Ev
  Cult's framework, examine the role of symmetry in design principles.
Investigates
  design principles as systems, revealing how aesthetic and functional patterns
  are systemically intertwined.
27
AI
Using Ev
  Cult's framework, explore the potential of AI in managing complex systems.
Examines
  AI through the Ev Cult perspective, highlighting the systemic nature of
  learning and adaptation in artificial systems.
28
AI (again!)
Use the Ev
  Cult fractal HOLON/parton lens to analyze the structure and function of
  neural networks in AI.
Demonstrates
  how AI neural networks exemplify fractal HOLON/partons, mirroring the
  complexity of biological learning systems.
29
Cryptoeconomics
Explore
  the systemic impact of cryptocurrencies on global financial systems using the
  principles of Ev Cult.
Decodes
  the systemic influences of digital currencies, projecting new insights into
  the evolution of financial systems.
30
Technological Development
Investigate
  the role of iterative design in technology development through the lens of
  fractal HOLON/partons.
Sheds
  light on how recursive methodologies in engineering reflect broader systemic
  patterns in technology evolution.
 This is a copy-paste from: 
Ev Cult GPT Prompts
.
 
Note also, that: 
 
Now, any time you ask your 
Ev Cult-enabled 
ChatGPT-4 any
question, it will also provide an answer within the meta-meta-scientific 
Ev
Cult
 framework...
 
(And, you’re
welcome... Enjoy!)
FYI - The 10 x Videos of this 
Ev Cult Short Course 
are also 
here, as a YouTube Playlist
.