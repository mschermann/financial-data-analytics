# Material for Financial Data Analytics

In the folder `data` you will find the extracts from the SEC dataset for

* [Logitech](https://www.sec.gov/cgi-bin/browse-edgar?action=getcompany&CIK=0001032975&owner=exclude&count=40
)
* [MagnaChip](https://www.sec.gov/cgi-bin/browse-edgar?action=getcompany&CIK=0001325702&owner=exclude&count=40&hidefilings=0
)

**Caution**: During the analysis, you may realize that filings are missing in the dataset (XBRL filing began in 2010 but the data may be a bit spotty). If you need to add date, you need to include the data manually. For instance, if you need the `AccountsReceivableNet` for Q1, Q2, Q3, and Q4, you need to add four rows to the data that contains the specific values.
