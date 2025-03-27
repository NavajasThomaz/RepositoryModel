<img align="center" style='position: fixed' width=50 src="https://github.com/NavajasThomaz/RepositoryModel/blob/main/static/images/3x4Redonda.png?raw=true" />

<div align="center">
<h1>/tasks</h1>
</div>

##### <div align="center">Contains code related to background jobs, asynchronous operations, or scheduled tasks, often implemented using <img src="https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54" target="_blank" width="70" align='center'> and task queues like <img src="https://img.shields.io/badge/celery-37814A?style=for-the-badge&logo=celery&logoColor=white" target="_blank" width="70" align='center'>.</div>

<div style=display:inline-block>
<img align="center" height=50 src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTpAq2i0YoBpm512rJCWDRZulLbATRWtcR3ug&s" />
: Holds definitions of Celery tasks (or similar frameworks like RQ) that can be executed asynchronously in the background, separate from the main web request cycle.
</div>
<div>
<img align="center" height=50 src="https://cdn-icons-png.flaticon.com/128/869/869636.png" />
: Can include logic for periodic or scheduled tasks (e.g., nightly reports, data cleanup) managed by tools like Celery Beat or system cron jobs invoking specific task functions.
</div>