# A-B-Testing

One of the core values is “Power of Proof”. This also applies to the development of features in our website. As such, we have run two A/B tests (testing different features, one in
February, the other in May) with a classical setup: show a control group to the majority of our users (constituting a subset of website visits), and a test group (containing the new feature)
to the remaining users (and corresponding remaining visits). You are provided with one csv file for each of these two tests, containing the results collected in terms of our main base metrics. 
The data is aggregated by ymd (the date), platform (the country-specific platform), and group (control or test). These are the first 3 columns of
the files. The remaining columns contain the base metrics:
* visits - how many website visits from our users were logged
* clicks - how many times our users clicked in one of our prices and were re-directed to the website of one of our advertisers. Note that each individual visit may or may not include clicks
* revenue - how much money (in EUR) was generated. You can work under the assumption that this revenue is generated under a CPC model.
* bookings - how many accommodation reservations were made in our advertisers’ websites.
* booking_amount - the corresponding amount (in EUR) paid by the users for the accommodation reservations.
