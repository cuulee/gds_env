---
layout: default
title: gds
parent: Stacks
nav_order: c 
---

{% include gds_README.md %}

## R Libraries

A full list of Python libraries installed in the `gds_py` environment is available below:

<details markdown="block">
  <summary type="button" name="button" class="btn">
        <code>`gds`</code> R library list (click to expand)
  </summary>
    
    {% include stack_r.md %}

</details>

[Download table as `.txt`](https://github.com/darribas/gds_env/raw/master/gds/stack_r.txt){: .btn .btn }

## Install

The Docker image can be downloaded with the following command:

```
docker pull darribas/gds:{{ site.gds_env.version }}
```
