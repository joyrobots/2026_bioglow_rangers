# Innovation Project Script

JoyRobots Rangers · full script in speaking order.

Rossy → Jason → Bowen → Jonathan → Jasper

---

## 1. Rossy · Identify

Did you know that mature ash trees have been almost completely wiped out across the Greater Toronto Area? The Toronto and Region Conservation Authority, TRCA, has already cut down over 45,000 ash trees. The emerald ash borer, or EAB, is an invasive beetle from Asia. It was first found in Ontario in 2002, and it kills unprotected ash trees. Its tiny larvae chew S-shaped tunnels under the bark that cut off the tree's food and water. Since they are hidden under the bark and cannot be seen from the outside, we have developed ArborListen to detect these larvae early.

Now Jason will talk about our design.

---

## 2. Jason · Design

What if we could find the EAB early, before the ash trees die? We compared three ideas: a camera, a microphone, and a vibration sensor. The larvae live under the bark, so a camera can't see them, and a microphone can't hear them. But when they chew under the bark, they make tiny vibrations in the wood. So we chose a piezoelectric sensor, which turns tiny vibrations into an electric signal. With it, we designed ArborListen to feel what we can't see or hear. From our sketches, we have a sensor that touches the bark, and an M5Stack that reads the signal and shows it on the screen.

Next, Bowen will tell you how our team created the solution.

---

## 3. Bowen · Create

How can a tiny computer feel a bug chewing inside a tree? ArborListen has two parts: a vibration sensor and an M5Stack. We programmed our sensor to detect the frequency of the vibrations that EAB larvae make. The M5Stack reads the signal, and its screen shows the tree's stats and the vibrations. Let me demo it. First, I press the "Ready" button. Now watch the screen when I scratch the wood. *(Scratch the wood. Point to the screen.)* The screen shows the vibration! A scratch is not a real larva, but it shows that our sensor can feel tiny vibrations in wood.

Next, Jonathan will tell you how we tested it and made it better.

---

## 4. Jonathan · Iterate

*(Show the video.)* I ride my bike at Bruce's Mill Conservation Area. An ash tree there was infested with EAB and had to be cut down. Our first version was a flat vibration sensor that sat on the bark. One problem we found is that it might not detect the larvae, because they are too small and the bark might be too thick. If it misses them, the ash tree might already be dead before we detect any sound. So for our second version, we added a needle to go deeper into the tree's bark, and we upgraded the sensor's sensitivity. We also searched for the hertz of the EAB larvae, so we can set the sensor to that exact hertz. For our next iteration, we plan to put a waterproof cover on the sensor.

Next, Jasper will talk about how we connected with experts.

---

## 5. Jasper · Communicate

Who knows best about ash trees? We asked TRCA and contacted a company called TreeAzin, with questions about the EAB and the white ash tree. We asked the experts about curing ash trees. We discovered that the medicine only works if the tree has lost less than 30% of its leaves. When most of the leaves in the crown of a tree are gone, it is too late to save the tree. That is why finding the EAB early matters. We showed them that we had made ArborListen, and told them we could use the vibration sensor to detect the EAB. They told us that our idea is a good one.

Now, when you see a white ash tree, you will think of our speech and our solution. Thank you for listening!
