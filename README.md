# voyage-tasks

Your project's `readme` is as important to success as your code. For 
this reason you should put as much care into its creation and maintenance
as you would any other component of the application.

If you are unsure of what should go into the `readme` let this article,
written by an experienced Chingu, be your starting point - 
[Keys to a well written README](https://tinyurl.com/yk3wubft).

And before we go there's "one more thing"! Once you decide what to include
in your `readme` feel free to replace the text we've provided here.

> Own it & Make it your Own!

## Team Documents

You may find these helpful as you work together to organize your project.

- [Team Project Ideas](./docs/team_project_ideas.md)
- [Team Decision Log](./docs/team_decision_log.md)

Meeting Agenda templates (located in the `/docs` directory in this repo):

- Meeting - Voyage Kickoff --> ./docs/meeting-voyage_kickoff.docx
- Meeting - App Vision & Feature Planning --> ./docs/meeting-vision_and_feature_planning.docx
- Meeting - Sprint Retrospective, Review, and Planning --> ./docs/meeting-sprint_retrospective_review_and_planning.docx
- Meeting - Sprint Open Topic Session --> ./docs/meeting-sprint_open_topic_session.docx

## Getting Started
1. Install pipenv
2. Install postgres
3. Create a `.env` file in the root 
4. Create a new database in postgres (I recommend using pgAdmin if you installed it too)
5. Open a terminal in the root
6. Run `pipenv install`
7. Run `pipenv shell`
8. Set the following values in the `.env` file:
9. Run `python manage.py makemigrations`
10. Run `python manage.py migrate`
11. Run `python manage.py runserver`

```
SECRET_KEY= 'THE_ACTUAL_KEY'
DATABASE_NAME = 
DATABASE_USER = 
DATABASE_PASSWORD = 
```