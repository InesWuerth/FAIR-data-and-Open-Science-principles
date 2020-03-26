# Introduction


Researchers spend most of their time preparing data for analysis instead of doing the analysis. A recent survey, reported by [Forbes](https://bit.ly/2WwVPho), showed that collecting, organizing, and cleaning data  (i.e., data preparation) accounts for 80% of researcher’s time, whereas the remaining 20% of their time is spend on the actual data analysis. Also the same survey indicated that 76% of researchers stated that the data preparation is the least favorable part of their work, which in effect maintains the state of "circulus vitiosus" where the legacy (e.g., data, code, etc.) of those who create or use data has a poor reusability. One of potential reasons for flagging the data preparation as the least favorable work is that this type of work is usually considered as engineering, thus not science. Therefore, data creators often do not receive a proper scientific recognition for their work.

We can look at this issue from another perspective. The amount of data we create is exponentially growing. In the past, those who created data were at the same analyzing them (almost) to the full extent. This resulted in the situation in which researchers who created data were selecting formats they were accustomed to, while omitting data description or not having a consistent approach in describing data since they were at the same time users of their own product. In the modern age, the amount of data is so large that those who create them can manage to analyze only a fraction of the entire dataset, where the remaining amount is left in ideal to be analyzed by other researchers.

To break the vicious circle it became evident and essential to establish and comply to certain guiding principles for data management and stewardship, divided the roles of data creators and data users in data lifecycle, and provide a proper scientific recognition to data creators. With respect to the data management and stewardship the [FAIR principles](https://www.nature.com/articles/sdata201618) represent the guiding principles initially endorsed by the [European Commission](https://ec.europa.eu/research/participants/data/ref/h2020/grants_manual/hi/oa_pilot/h2020-hi-oa-data-mgt_en.pdf) (EC) and now globally pursued. The FAIR principles stand for making data **F**indable, **A**ccessible, **I**nteroperable and **R**eusable (FAIR) by humans and but even more importantly by **machines**. In the following sections we will review each principle individually. To large extent the material for the sections is compiled from [GO FAIR](https://www.go-fair.org/) web site (material permitted for reuse under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) license).

![FAIR principles](./img/FAIR_data_principles.jpg)
**Figure 1.** FAIR principles (source: [Sangya Pundir, Wikipedia](https://commons.wikimedia.org/w/index.php?title=User:SangyaPundir&action=edit&redlink=1) license [CC BY SA](https://creativecommons.org/licenses/by-sa/4.0/deed.en))

> _Data_ means anything that contains some kind of information. One could apply the FAIR principles to anything from a text document to an e-mail to a lidar data set to code. In general, though, because they are the most valuable type of data (i.e. the hardest to recreate), we usually think of data as meaning a classical data set obtained from a measurement or simulation.

# F - Findable
The first step in (re)using data is to find them. Metadata and data should be easy to find for both humans and computers. Machine-readable metadata are essential for automatic discovery of datasets and services, so this is an essential component of the [FAIRification](https://www.go-fair.org/fair-principles/fairification-process/) process. Under the **Findable** facet of the FAIR principles we have four principles.


> F1. (Meta)data are assigned a globally unique and persistent identifier



> F2. Data are described with rich metadata (defined by R1 below)


> F3. Metadata clearly and explicitly include the identifier of the data they describe


>F4. (Meta)data are registered or indexed in a searchable resource


# A - Accessible
Once the user finds the required data, she/he needs to know how can they be accessed, possibly including authentication and authorization. Here we have two principle, where one of them is further decoupled to two sub-principles:

> A1. (Meta)data are retrievable by their identifier using a standardized communications protocol.
>> A1.1 The protocol is open, free, and universally implementable<br> <br>
>>A1.2 The protocol allows for an authentication and authorization procedure, where necessary



# I - Interoperable

# R - Reusable
