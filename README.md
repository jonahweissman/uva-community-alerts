# UVA Community Alerts

When is it too late to walk home alone? I don't know, but I can show you a histogram of the times of incidents that Timothy Longo told us all about. Check out [Analysis.ipynb](https://github.com/jonahweissman/uva-community-alerts/blob/main/Analysis.ipynb) or run a local copy if you want to tinker:
```
pip install -r requirements.txt
jupyter lab
```
In the notebook, I display both the time of the email alert and the reported time of the event.

## Next Steps

There probably isn't enough data to do this, but I'm very curious if the likelihood of an event occuring increases earlier in the evening during the darker months of the year.



## Data source

I searched my UVA inbox for emails with "Community Alert" in the subject line and exported these using Google Takeout. I removed some headers and took out tracking links for privacy.

## License

MIT
