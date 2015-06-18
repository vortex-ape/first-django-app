# Polls

Polls is a simple Django app to conduct Web-based polls. For each
question, visitors can choose between a fixed number of answers.

## Quick start

1. Add "polls" to your INSTALLED\_APPS setting like this:

    <pre>
    INSTALLED_APPS = (
        ...
        'polls',
    )
    </pre>        

2. Include the polls URLconf in your project urls.py like this::

    <pre>url(r'^polls/', include('polls.urls')),</pre>

3. Run `python manage.py migrate` to create the polls models.

4. Start the development server and visit http://127.0.0.1:8000/admin/
   to create a poll (you'll need the Admin app enabled).

5. Visit http://127.0.0.1:8000/polls/ to participate in the poll.

