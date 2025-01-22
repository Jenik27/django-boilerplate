# {{ cookiecutter.project_name }}

{{ cookiecutter.description }}

## Local Development 

{% if cookiecutter.use_docker == 'y' %}
### Docker

See detailed deployment with Docker documentation.

{% endif %}
{% if cookiecutter.frontend_pipeline in ['Gulp', 'Webpack'] %}

### Custom Bootstrap Compilation

The generated CSS is set up with automatic Bootstrap recompilation with variables of your choice.
Bootstrap v5 is installed using npm and customised by tweaking your variables in `static/sass/custom_bootstrap_vars`.

{% endif %}
