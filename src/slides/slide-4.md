class: center, middle, inverse

# So what? <br> Look at all these tickets!

---

class: center, middle, inverse

# So what? <br> Look at all these tickets!

<br><br>
.shiftDown[see what I did there]

---

# How could TodayTix Engineering benefit?

- Environment consistency.

- Developer productivity.

- Low-risk way to ease into "breaking up the monolith".

---

# The "Lift and Shift"

> With the monolithic application running in a container, the development team can start breaking it down piece by piece. They can move some functions out of the monolith, and begin deploying them as loosely coupled services in Docker containers.

---

class: center, middle, inverse

# Get ya demo on 💃

---

class: center, middle, inverse

# What's next?

---

class: center, middle

# Embrace progress;<br> avoid the shiny things.

---

class: center, middle

# State of containerization in 2017

.center.middle[![](https://cdn.meme.am/cache/instances/folder723/500x/58060723/will-it-blend-guy-yes-but-will-it-blend.jpg)]
---

# Potential projects

- Automated daily generation of MySQL DB images from PROD, uploaded to a private container repo.
  - Developers can pull the latest image, and always have up-to-date data. Reduce incidence of "works on my machine!" bugs.
  - Immutability is "built-in", so preventing conflicts/discrepancies between environments is easy.

---

# Potential projects

- Making spinning up new instances a trivial, inexpensive task.
  - Ansible + Docker = 😍
  - If time to boot & provision new instances is negligible, we can eliminate our current "environment bottleneck".

---

class: center, middle, inverse

# Which means less of this:

![](https://cl.ly/3U0o3K342W38/1nndb7.jpg)

---

class: center, middle, inverse

# And more of this.

![](https://cl.ly/2j2s1h2g290O/coder.png)

---

class: center, middle, inverse

# And most importantly, this.

![](https://cl.ly/3J44330a0j35/happiness.png)
