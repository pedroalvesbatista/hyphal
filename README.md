# Hyphal
Hyphal Community-driven Container Registry


## Where does the name hyphal come from ?

[Hyphal networks](https://en.wikipedia.org/wiki/Hypha) or hyphae in plural, consists of a web of hypha (or "web" in greek), a long branch filamentous structure of fungus, oomycyte or actinobacterium organisms. For most fungi, hyphae are the main mode for vegetative growth, and in collectively they form a [mycelium network](https://en.wikipedia.org/wiki/Mycelium).


## Why a community-driven container registry project ?

Centralized systems that serves multi-purpose such as container images registry, like Docker Hub, are struggling with [some limitaions](https://thenewstack.io/docker-hub-limits-what-they-are-and-how-to-route-around-them/).

Some companies, like Amazon Web Services (AWS) [does have](https://gallery.ecr.aws/) a public "gallery" container registry.

## Borrowed ideas

Some inspiration was caught from existing projects, like :

* [Open Container Initiative - OCI](https://opencontainers.org/about/overview/)
* [Portus](https://port.us.org)
* [Harbor](https://goharbor.io)
* [Hinkskalle](https://github.com/csf-ngs/hinkskalle) - Most of the heavy-lift inspiration for this project came from here, as the main goal is to re-write Hinkskalle to Golang to provide full Singularity containers capabilities (this capilarity, also referenced as "myelination", from nerve cells axons myelin substance, and can extend to other container runtimes also).

Those projects provides the basis for Hyphal, as well some enlightment on how to deal with OCI-compliant container registry systems. If you do have any other project to indicate, please, send a PR (check [CONTRIBUTING](https://github.com/pedroalvesbatista/hyphal/tree/master/CONTRIBUTING.md) for further details).