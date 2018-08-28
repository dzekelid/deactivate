---
swagger: "2.0"
x-collection-name: Mattermost
x-complete: 0
info:
  title: Mattermost API Deactivate plugin
  description: |-
    Deactivate a previously activated plugin. Plugins must be enabled in the server's config settings.

    ##### Permissions
    Must have `manage_system` permission.

    __Minimum server version__: 4.4
  termsOfService: https://about.mattermost.com/default-terms/
  version: 4.0.0
host: your-mattermost-url.com
basePath: /api/v4
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /users/{user_id}:
    delete:
      summary: Deactivate a user account.
      description: |-
        Deactivates the user by archiving its user object.
        ##### Permissions
        Must be logged in as the user being deactivated or have the `edit_other_users` permission.
      operationId: deactivates-the-user-by-archiving-its-user-object-permissionsmust-be-logged-in-as-the-user-being-dea
      x-api-path-slug: usersuser-id-delete
      parameters:
      - in: path
        name: user_id
        description: User GUID
      responses:
        200:
          description: OK
      tags:
      - Deactivate
      - User
      - Account.
  /plugins/{plugin_id}/deactivate:
    post:
      summary: Deactivate plugin
      description: |-
        Deactivate a previously activated plugin. Plugins must be enabled in the server's config settings.

        ##### Permissions
        Must have `manage_system` permission.

        __Minimum server version__: 4.4
      operationId: deactivate-a-previously-activated-plugin-plugins-must-be-enabled-in-the-servers-config-settings-perm
      x-api-path-slug: pluginsplugin-iddeactivate-post
      parameters:
      - in: path
        name: plugin_id
      responses:
        200:
          description: OK
      tags:
      - Deactivate
      - Plugin
x-streamrank:
  polling_total_time_average: 0
  polling_size_download_average: 0
  streaming_total_time_average: 0
  streaming_size_download_average: 0
  change_yes: 0
  change_no: 0
  time_percentage: 0
  size_percentage: 0
  change_percentage: 0
  last_run: ""
  days_run: 0
  minute_run: 0
---