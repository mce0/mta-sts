# MTA-STS support for my custom domain on Proton Mail

> To this date, [Proton Mail doesn’t support MTA-STS for custom domains](https://old.reddit.com/r/ProtonMail/comments/y6q6g8/mtasts_for_custom_domains/). While DANE for SMTP is a much better solution to the same problem, MTA-STS exists for a reason: many providers are slow at adopting DNSSEC. DNSSEC is essential to enabling standards such as DANE or SSHFP. Notably, [Gmail still does not support DANE](https://www.hardenize.com/report/gmail.com/1689164394#email_dane) but has supported MTA-STS for years.
> 
> Therefore, MTA-STS and DANE can complement each other, and you should ideally deploy both.

From [wonderfall.dev/mta-sts](https://wonderfall.dev/mta-sts/)
