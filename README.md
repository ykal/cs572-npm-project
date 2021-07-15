### MEAN Games Google Anaylytics using `ngx-google-analytics`

#### Main tasks completed

* Track every page visit in the application.
  * Since angular is a SPA, tracking each page visit is triky. The package listens to every route change and tracks the visit.
  * In MEAN Games all routes are tracked.
    * `auth/register`
    *  `games`
    *  `games/:gameId`
    *  `profile`
* Track other activities shuch as searching, inserting input ...
  * for this showcase I have implemented tracking of searching activity.