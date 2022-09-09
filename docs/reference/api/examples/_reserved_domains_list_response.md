
###### Example Response
```
{
  "reserved_domains": [
    {
      "id": "rd_2E8b1umGIBPUUcNOYkUD7kYBtB9",
      "uri": "https://api.ngrok.com/reserved_domains/rd_2E8b1umGIBPUUcNOYkUD7kYBtB9",
      "created_at": "2022-08-31T21:05:46Z",
      "description": "Device 0001 Dashboard",
      "metadata": "{\"service\": \"dashboard\"}",
      "domain": "manage-0001.app.example.com",
      "region": "us",
      "cname_target": "2j6va8f4y.cname.us.ngrok.io",
      "http_endpoint_configuration": null,
      "https_endpoint_configuration": null,
      "certificate": null,
      "certificate_management_policy": {
        "authority": "letsencrypt",
        "private_key_type": "ecdsa"
      },
      "certificate_management_status": {
        "renews_at": null,
        "provisioning_job": {
          "error_code": null,
          "msg": "Managed certificate provisioning in progress.",
          "started_at": "2022-08-31T21:05:46Z",
          "retries_at": null
        }
      },
      "acme_challenge_cname_target": null
    },
    {
      "id": "rd_2E8b1tza5GWpkg84QtHOh8vKemy",
      "uri": "https://api.ngrok.com/reserved_domains/rd_2E8b1tza5GWpkg84QtHOh8vKemy",
      "created_at": "2022-08-31T21:05:46Z",
      "description": "",
      "metadata": "",
      "domain": "myapp.mydomain.com",
      "region": "us",
      "cname_target": "2vmqcnryy.cname.us.ngrok.io",
      "http_endpoint_configuration": null,
      "https_endpoint_configuration": null,
      "certificate": {
        "id": "cert_2E8b1kFAMvEiyadu68JDbjakz4G",
        "uri": "https://api.ngrok.com/tls_certificates/cert_2E8b1kFAMvEiyadu68JDbjakz4G"
      },
      "certificate_management_policy": null,
      "certificate_management_status": null,
      "acme_challenge_cname_target": null
    }
  ],
  "uri": "https://api.ngrok.com/reserved_domains",
  "next_page_uri": null
}