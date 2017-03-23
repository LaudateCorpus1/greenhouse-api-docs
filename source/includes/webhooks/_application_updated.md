## Application updated

```json
{
  "action": "application_updated",
  "payload": {
    "application": {
      "id": 22202940,
      "rejected_at": null,
      "prospect": false,
      "status": "active",
      "applied_at": "2015-12-03T06:31:26Z",
      "last_activity_at": "2015-12-03T06:31:26Z",
      "url": "https://app.greenhouse.io/people/13857579?application_id=22202940",
      "source": {
        "id":2,
        "name": "Jobs page on your website"
      },
      "credited_to": {
        "id": 3695,
        "email": "beauregard.blacksmith.3695@example.com",
        "name": "Beauregard Blacksmith"
      },
      "rejection_reason": null,
      "rejection_details": null,
      "current_stage": {
        "id": 711020,
        "name": "Application Review",
        "interviews": [
          {
            "id": 1063685,
            "name": "Application Review",
            "status": "collect_feedback",
            "interview_kit": {
              "url": "http://app.greenhouse.io/guides/1063859/people/13857579",
              "content": "",
              "questions":[]
            },
            "interviewers": []
          }
        ]
      },
      "custom_fields": {
        "custom_application_field": {
          "name": "Custom Application Field",
          "type": "short_text",
          "value": "Example"
        }
      },
      "candidate": {
        "id": 13857579,
        "first_name": "Hank",
        "last_name": "Von Diablo",
        "title": null,
        "company": null,
        "created_at": "2015-12-03T06:31:26Z",
        "external_id": null,
        "photo_url": "https://photo.com/photo.jpg",
        "url": "https://app.greenhouse.io/people/13857579",
        "phone_numbers": [
          {
            "value": "330-281-8004",
            "type": "other "
          }
        ],
        "email_addresses": [
          {
            "value": "hank.von diablo.13857579@example.com",
            "type": "personal"
          }
        ],
        "addresses": [],
        "website_addresses": [
          {
            "value": "http://www.example.com/",
            "type": "other"
          }
        ],
        "social_media_addresses": [
          {
            "value": "https://twitter.com/TheRock"
          }
        ],
        "educations": [],
        "recruiter":null,
        "coordinator": null,
        "attachments":[],
        "tags":[],
        "custom_fields": {
          "current_salary": {
            "name": "Current Salary",
            "type": "short_text",
            "value": null
          },
          "desired_salary": {
            "name": "Desired Salary",
            "type": "short_text",
            "value":null
          }
        }
      },
      "jobs": []
    }
  }
}


```

The Application Updated event occurs when an application is updated.

See web hook [common attributes](#common-attributes).