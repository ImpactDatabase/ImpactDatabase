## Hosting Options For Metabase + Superset Self-Managed Deployments

The following lists some options for running the two data viz tools that I've looked at the most closely with approximate costs. I'm using the term "self managed" instead of "self hosted" intentionally because it better reflects the objective for choosing this architecture:

| Service            | Provider               | Notes                                                        | Cost (Approx)                                                |
| ------------------ | ---------------------- | ------------------------------------------------------------ | ------------------------------------------------------------ |
| Google Cloud (GCP) | Metabase               | There's a standalone image but getting Metabase set up on Google Kubernetes Engine (GKE) is quite straightforward |                                                              |
| Google Cloud       | Superset               | Superset is a more involved workload that brings a few moving parts into the picture including Nginx, Redis, a websocket, Solr, and more. Helpfully, Google has a ready to run image that can be deployed directly into GKE. | The test image I ran would have yielded monthly billing of about $100 |
| Restack            | Metabase  and Superset | Restack is a nice looking tool that allows users to deploy common open source packages. Their library of data tools includes all the main "players" including Metabase, Superset, Redash, Lightdash, Grafana, and more | Varies by image but their prices seem more favorable than those obtained by provisioning directly on GCP |
| Railway            | Haven't checked        | The "we make it easy to deploy OS" space is getting pretty crowded. Railway looks good as well. Haven't gone through packages and pricing yet |                                                              |
| Coolify            | As above               | As above ... another PaaS option                             |                                                              |
| Elestio            |                        | Gave them a test run hosting Superset and  Metabase but ran into credentials issues. Their prices are pretty reasonable, however. |                                                              |
| Preset             |                        | Managed Superset deployments with very close links to the project itself |                                                              |
| AWS                |                        | AWS has a ready to go image for Superset in its marketplace library |                                                              |
| Plural.sh          |                        | This one is a very interesting provider! It's a self-hosted Kubernetes fleet management tool. Ie, this is a deployment architecture that you can self host! |                                                              |
| Digital Ocean      |                        | DO has an image for Metabase but not Superset                |                                                              |

