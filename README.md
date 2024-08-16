# Waymo Case Study

## Overview and Origin

Waymo is a self-driving car company, with roots placing the initial development occurring due to the 
2005 DARPA Grand Challenges, founded by Sebastian Thrun and Anthony Levandowski. After several years of work, 
in 2009 it was expanded into the Google Self-Driving Car Project, then incorporated as an independent company in 2016.
Currently, Waymo is funded through rounds of external investment, currently having raised $5.5 billion through multiple waves.
> Prior to this, Waymo raised $2.3 billion in its first external funding round in 2020. The company raised 
another $2.5 billion in 2021 in a round that included funding from Andreessen Horowitz, AutoNation , 
Canada Pension Plan Investment Board, Fidelity Management and Research Company and more. [6] (https://coverager.com/alphabet-to-invest-5-billion-in-waymo/)

## Landscape

When it comes to self-driving cars, the main companies that are at play would be Waymo (Google), Zoox (Amazon), 
Cruise (General Motors), and Rivian (Amazon). This is a fairly new industry, and biggest thing would
be the advancements from level 2, which is effectively manual with some help to level 4, where the human is 
there for emergencies and if road conditions become very bad. The trend is to end up at level 5, 
where a human operator is completely unneeded. [26] (https://en.wikipedia.org/wiki/History_of_self-driving_cars)

## Business Activities

A primary goal of Waymo is to ensure safety of the roads. and in doing so, allow a superior transportation system 
as seen by their official mission statement:
> Every year, 1.4M lives are lost to traffic crashes around the world. The status quo is not acceptable. 
Waymo is committed to holding safety to a higher standard. Because when we do, we make space for people to get 
around in a whole new way. On this path, we aim to offer freedom of movement for all, create a sustainable, efficient 
transportation ecosystem and make the planet better than we found it. [1] (https://waymo.com/)

According to the National Highway Traffic Safety Administration [17] (https://crashstats.nhtsa.dot.gov/Api/Public/ViewPublication/812115)
, approximately 94% of crashes in the US are due to human error. 
> A critical reason can be assigned to a driver, vehicle, or environment. Normally, one critical reason was 
assigned per crash, based upon NMVCCS researcher’s crash assessment. The critical reason
was assigned to the driver in an estimated 94 percent (±2.2%) of
the crashes (Table 1). In addition, the critical reason was assigned
to the vehicle in an estimated 2 percent (±0.7%) and to the environment in about 2 percent (±1.3%) of the crashes.

By taking the human factor out of the car, Waymo is able to commit to securing safety 
on the roads. This is paired with the goal of having autonomous cars accessible to the standard 
user through ride share services. According to pymnts [18] (https://www.pymnts.com/innovation/2019/who-will-use-self-driving-cars/),
there is an interest in some form of ride share based utilizing self-driving vehicles, although people are still more skeptical 
and not yet trusting when it comes to putting their and their family’s safety in their hand, 
showing that trust still needs to be developed.

Waymo cars navigate their environment using a combination of LiDAR, cameras, microphones, and HD maps. 
LiDAR, which fires lasers to build a data cloud of the envionment, is effective both in light and dark environments and is
capable of "seeing" far distances, which is valuable when it comes to operating at high speeds, like on a highway. 
There are cameras capable of operating in both standard and low light conditions,
that allow the Waymo to get a 360-degree view of the world around it as a human would see it, allowing for visual identification of
traffic lights and signs, to effectively follow the rules of the road.  Microphones are used to identify EMS sirens in order to give way.
Finally, HD maps act mostly for the sake of planning ahead. 
> High Definition (HD) maps are maps with precise definitions of road lanes with rich semantics of the traffic rules. 
They are critical for several key stages in an autonomous driving system, including motion forecasting and planning. 

The main advantage that Waymo has over its competitors would be being a pioneer as well as their prioritization of safety. Being a 
pioneer is advantageous to them as it allowed for them to strike deals with cities to allow for Waymo to gather their test data without
having to worry about dealing with a competitor also trying to gather data from the same city. Their prioritization of safety helps
in that they can work for lower accident rates, to help ensure trust doesn't break.

## Issues

The primary issues that Waymo faces are ones of scaling. LiDAR is expensive, which resists Waymo's ability
to scale their fleet. An additional issue in terms of scale would simply be the issue with wanting to have people get personal
self-driving cars, rather than ridesharing with a fleet. This makes maintenance and ensuring the sensor function to be significantly
harder, and becomes an insurance and liability nightmare. This likely acts as an additional deterrent in the ability to expand. 
An additional issue would be how any crash damages perceptions of Waymo as a whole, *regardless of fault*. 
> Any collision involving an autonomous vehicle — even one in which the company is not at fault — can cause a backlash, 
particularly in a city like San Francisco, where there is already tension between city officials, 
AV tech companies and the public. If technological capability and a favorable regulatory environment are 
two legs of a solid AV commercialization stool, public perception is the crucial third. And a self-driving car 
killing a sweet pooch has the potential to kick out that third leg.
[25] (https://techcrunch.com/2023/06/06/a-waymo-self-driving-car-killed-a-dog-in-unavoidable-accident/)

## Results

Because Waymo pioneered the self-driving car industry, they have had the greatest impact in terms of the direction that it goes, 
and the legislation that is written to regulate it as well. Said legislation being with regards to operation of autonomous vehicles,
how collisions are handled, and restrictions that are placed on them. [27] (https://www.repairerdrivennews.com/2024/04/26/legislation-restricting-self-driving-vehicles-proposed-in-california/)
They have also established metrics, and how they are measured. A core one used by Waymo is safety compared to human 
drivers, which they excel at.
> An 85% reduction or 6.8 times lower crash rate involving any injury, from minor to severe and fatal cases 
(0.41 incidence per million miles for the Waymo Driver vs 2.78 for the human benchmark)
A 57% reduction or 2.3 times lower police-reported crash rate (2.1 incidence per million miles for 
the Waymo Driver vs. 4.85 for the human benchmark) [12] (https://waymo.com/blog/2023/12/waymo-significantly-outperforms-comparable-human-benchmarks-over-7-million/) <br>
![Waymo % Change for Police / Injury-Reported Rate] (https://images.ctfassets.net/e6t5diu0txbw/4gzabJgoo5jGxaCWZpKo0e/13de274b9ca40a8149d79dc8ee99fcef/pasted_image_0.png?fm=webp)

Waymo is currently leading the pact in the industry. Both Uber and Apple had programs to attempt at self-driving cars, 
but have terminated their respective programs. Cruise, on the other hand, went at their cars with different focuses, and have
currently suspended their self-driving ride share service. Finally, Zoox is operating on a smaller scale, as transport within a campus
rather than along cities proper.

## Recommendations

If I was to advise them, then I would suggest seeing about providing self-driving buses, since it would both spread trust and allow
them to gather more autonomous miles to log and improve maps. The only real major technology that would need to be implemented
would be having the cameras be able to identify passengers wanting to get on the bus. In addition, with the potential legislation
requiring agreements to be made before being able to operate in a city, being able to have the city offload the cost of operating 
public transit to them could be a viable business tactic.

## Sources
1. https://waymo.com/
2. https://en.wikipedia.org/wiki/Waymo
3. https://www.cnbc.com/2022/05/21/why-the-first-autonomous-vehicles-winners-wont-be-in-your-driveway.html
4. https://www.theverge.com/2021/6/16/22536593/waymo-funding-round-amount-investors-av
5. https://www.crunchbase.com/organization/waymo/company_financials
6. https://coverager.com/alphabet-to-invest-5-billion-in-waymo/
7. https://www.lawinfo.com/resources/car-accident/how-many-car-accidents-are-caused-by-human-er.html
8. https://crashstats.nhtsa.dot.gov/Api/Public/ViewPublication/812115
9. https://www.pymnts.com/innovation/2019/who-will-use-self-driving-cars/
10. https://www.zippia.com/waymo-careers-1418404/competitors/#
11. https://finance.yahoo.com/news/waymo-outlasted-competition-made-robo-100000830.html
12. https://waymo.com/blog/2023/12/waymo-significantly-outperforms-comparable-human-benchmarks-over-7-million/
13. https://www.firstent.org/blog/what-to-do-if-you-get-in-an-accident-with-one-of-l-a-s-new-driverless-cars/#:~:text=And%20under%20California%20law%2C%20the,damage%20resulting%20from%20the%20accident.
14. https://fortune.com/2024/05/29/waymo-self-driving-robo-taxi-uber-tesla-alphabet/
15. https://waymo.com/blog/2021/08/addressing-transit-mobility-gaps-what/
16. https://media.renaultgroup.com/autonomous-vehicle-renault-group-to-soon-launch-an-ambitious-level-4-offer-for-public-transportation/
17. https://crashstats.nhtsa.dot.gov/Api/Public/ViewPublication/812115
18. https://www.pymnts.com/innovation/2019/who-will-use-self-driving-cars/
19. https://torc.ai/2024/01/01/understanding-the-levels-of-autonomy-3-4-5/
20. https://www.hesaitech.com/benefits-of-lidar-vs-cameras-in-self-driving-cars/
21. https://support.google.com/waymo/answer/9190819?hl=en
22. https://waymo.com/research/hdmapgen-a-hierarchical-graph-generative-model-of-high-definition-maps/
23. https://www.reddit.com/r/SelfDrivingCars/comments/1cdn5e7/the_role_of_high_def_maps/
24. https://www.reddit.com/r/SelfDrivingCars/comments/14b1beu/when_do_you_think_waymo_or_cruise_will_be/
25. https://techcrunch.com/2023/06/06/a-waymo-self-driving-car-killed-a-dog-in-unavoidable-accident/
26. https://en.wikipedia.org/wiki/History_of_self-driving_cars
27. https://www.repairerdrivennews.com/2024/04/26/legislation-restricting-self-driving-vehicles-proposed-in-california/
28. https://www.popsci.com/technology/self-driving-car-companies-status/
29. https://www.linkedin.com/pulse/googles-waymo-vs-tesla-self-driving-car-race-dr-amr-elharony-srcef/
