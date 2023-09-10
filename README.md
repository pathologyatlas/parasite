







```
r language parasite, echo=FALSE, include=TRUE
source("./R/language.R")
output_type <- knitr::opts_knit$get("rmarkdown.pandoc.to")
```


```
asis parazit TR, echo = (language == "TR")
## parasite - parazit {#sec-parasite }
```


```
asis parasite EN, echo = (language == "EN")
## parasite - parasite {#sec-parasite }
```






```
r parasite screenshot HE, eval=TRUE, include=FALSE
if (!file.exists("./screenshots/thumbnail_parasite-HE.png")) {
webshot2::webshot(
  url = "https://images.patolojiatlasi.com/parasite/HE.html",
  file = "./screenshots/thumbnail_parasite-HE.png"
)
}
```





::::: panel-tabset


### WSI - Link










[https://images.patolojiatlasi.com/parasite/HE.html](https://images.patolojiatlasi.com/parasite/HE.html)





```
asis, echo = (language == "TR")

**parazit**


[![Tam Ekran Görmek İçin Resmi Tıklayın](./screenshots/thumbnail_parasite-HE.png){width="25%"}](https://images.patolojiatlasi.com/parasite/HE.html) [Tam Ekran Görmek İçin Resmi Tıklayın](https://images.patolojiatlasi.com/parasite/HE.html)
```

```
asis, echo = (language == "EN")

**parasite**

[![Click for Full Screen WSI](./screenshots/thumbnail_parasite-HE.png){width="25%"}](https://images.patolojiatlasi.com/parasite/HE.html) [Click for Full Screen WSI](https://images.patolojiatlasi.com/parasite/HE.html)

```





### WSI








```
asis, echo = ((language=="TR") & (output_type=="html"))
Mikroskopik görüntüleri inceleyin:

<iframe src="https://images.patolojiatlasi.com/parasite/HE.html" style="height:600px;width:100%;" data-external="1"></iframe>

```





```
asis, echo = ((language == "EN") & (output_type=="html"))

See Microscopy with viewer:

<iframe src="https://images.patolojiatlasi.com/parasite/HE.html" style="height:600px;width:100%;" data-external="1"></iframe>

```





### Diagnosis


```
asis, echo = (language == "TR")


::: {.callout-tip collapse="true" appearance="default" icon="true"}
### Tanı için tıklayın

parazit

:::


```


```
asis, echo = (language == "EN")


::: {.callout-tip collapse="true" appearance="default" icon="true"}
### Click for Diagnosis

parasite

:::

```









:::::








