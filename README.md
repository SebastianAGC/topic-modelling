# topic-modelling
Topic modelling 

1. The data used was extracted with a scrapper from Wikipedia featured articles.

2. Hyperparameters used:

- Number of topic: 10 
- Alpha = 'auto' 
- Beta = 1

5. Topic interpretation:

(0,
  '0.018*"hawaiian" + 0.005*"combatant" + 0.005*"native_hawaiian" + '
  '0.005*"missionary" + 0.004*"descendant" + 0.004*"american_civil" + '
  '0.003*"document" + 0.003*"descent" + 0.003*"record" + 0.003*"unmarked"')

Topic: United States Military

(1,
  '0.017*"hoard" + 0.016*"find" + 0.008*"silver" + 0.008*"ditch" + '
  '0.008*"item" + 0.008*"coin" + 0.006*"enclosure" + 0.005*"gold" + '
  '0.005*"treasure" + 0.005*"date"')

Topic: Treasures/Currencies/Mining

(2,
  '0.009*"war" + 0.008*"force" + 0.005*"begin" + 0.005*"french" + 0.005*"army" '
  '+ 0.005*"also" + 0.005*"defeat" + 0.005*"end" + 0.005*"battle" + '
  '0.005*"siege"')

Topic: War

(3,
  '0.019*"attack" + 0.012*"force" + 0.012*"german" + 0.009*"operation" + '
  '0.008*"capture" + 0.007*"battle" + 0.006*"town" + 0.006*"ship" + '
  '0.006*"also" + 0.006*"raid"')

Topic: War

(4,
  '0.011*"diocletian" + 0.009*"building" + 0.009*"design" + 0.007*"window" + '
  '0.007*"penis" + 0.006*"style" + 0.006*"show" + 0.005*"room" + '
  '0.005*"temple" + 0.005*"house"')

Topic: Roman Architecture

(5,
  '0.002*"ledge" + 0.001*"pinnacle" + 0.001*"furlough" + 0.001*"tunisian" + '
  '0.000*"feedback" + 0.000*"vocalise" + 0.000*"commandeer" + 0.000*"rankle" + '
  '0.000*"abdominal" + 0.000*"receptiveness"')

Topic: Anatomy

(6,
  '0.009*"man" + 0.006*"officer" + 0.005*"make" + 0.005*"order" + 0.005*"time" '
  '+ 0.005*"become" + 0.005*"return" + 0.004*"serve" + 0.004*"first" + '
  '0.004*"also"')

Topic: Police/Military

(7,
  '0.000*"make" + 0.000*"force" + 0.000*"return" + 0.000*"also" + 0.000*"lead" '
  '+ 0.000*"first" + 0.000*"include" + 0.000*"building" + 0.000*"time" + '
  '0.000*"later"')

Topic: Undefined

(8,
  '0.016*"disk" + 0.010*"formation" + 0.010*"star" + 0.008*"accretion" + '
  '0.008*"planet" + 0.007*"form" + 0.007*"mass" + 0.007*"gas" + '
  '0.006*"planetesimal" + 0.005*"core"')

Topic: Celestial Bodies

(9,
  '0.011*"season" + 0.009*"first" + 0.009*"team" + 0.007*"play" + 0.007*"game" '
  '+ 0.007*"building" + 0.006*"make" + 0.006*"run" + 0.006*"time" + '
  '0.005*"year"')

Topic: Sports

5. We chose game-development related articles for the last exercise and our topic model gave us the following topics.

Hyperparameters:

- Number of topics: 5
- Alpha: 'auto'
- Beta: 1

 (0,
  '0.027*"game" + 0.013*"computer" + 0.013*"console" + 0.013*"video_game" + '
  '0.012*"development" + 0.012*"develop" + 0.010*"first" + 0.010*"developer" + '
  '0.009*"produce" + 0.009*"usually"')

Topic: Game Development

 (1,
  '0.025*"engine" + 0.022*"game" + 0.010*"design" + 0.010*"technology" + '
  '0.010*"first" + 0.010*"code" + 0.008*"write" + 0.008*"software" + '
  '0.008*"support" + 0.007*"base"')

Topic: Software Development

 (2,
  '0.033*"model" + 0.018*"render" + 0.018*"dimensional" + 0.015*"computer" + '
  '0.015*"graphic" + 0.015*"image" + 0.015*"display" + 0.011*"technique" + '
  '0.011*"datum" + 0.011*"representation"')

Topic: Computer Graphics

 (3,
  '0.028*"game" + 0.016*"computer" + 0.015*"console" + 0.012*"animation" + '
  '0.010*"engine" + 0.010*"video_game" + 0.010*"use" + 0.009*"base" + '
  '0.009*"image" + 0.008*"industry"')

Topic: Game Development

 (4,
  '0.022*"game" + 0.022*"cost" + 0.014*"estimate" + 0.010*"gameplay" + '
  '0.010*"budget" + 0.008*"also" + 0.008*"development" + 0.008*"video_game" + '
  '0.008*"console" + 0.008*"high"')
 
Topic: Game Industry

As we can see in the output topics, all topics are related to the theme we chose to give as input.