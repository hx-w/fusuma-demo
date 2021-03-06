<!-- section-title: Cover -->

# Cutting Algorithm

<br />

by He Xiang

---

<!-- section-title: Overview -->

## Algorithm Overview

<!-- block-start: grid -->

<!-- block-start: column, left -->

```
[INPUT]

2-manifold triangle mesh M (irregular) 


[OUTPUT]

Final cut  (set of edges)
```

<!-- block-end -->
<!-- block-start: column, left -->

obj file format

```md
v 1.0 1.0 1.0

v 2.0 2.0 2.0

f 1// 2// 3//

f 2// 3// 4//
```

<!-- block-end -->
<!-- block-end -->

---

<!-- section-title: Total Steps-->

## Algorithm Steps

<!-- block-start: grid -->
<!-- block-start: column, left -->

```
[STEP 1] Find topologically-sufficient cut


[STEP 2] Augment cut
```
<!-- block-end -->
<!-- block-end -->

---

<!-- section-title: Step-1 -->

## STEP 1

<!-- block-start: grid -->
<!-- block-start: column, left -->

```
[STEP 1.1] Remove seed triangle

[STEP 1.2 *] Remove some edge and triangle

[STEP 1.3 *] Remove some vertex and edge

[STEP 1.4] Straighten the loops if exists 

[STEP 1.5] If no vertex left, add back two edges
```

<!-- block-end -->
<!-- block-end -->

---

<!-- block-start: grid -->

### [STEP 1.2]

<img src="https://ibed.csgowiki.top/image/20220224103546.png" alt="step1.2" style="zoom:50%;" />

### [STEP 1.3]

<img src="https://ibed.csgowiki.top/image/20220224103613.png" alt="step1.3" style="zoom:50%;" />

<!-- block-end -->

---

<!-- section-title: Bye👋 -->

## Bye👋
