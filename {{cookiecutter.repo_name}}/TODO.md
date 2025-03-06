# Next steps for your skill

- [ ] Push to a GitHub repository to enable automations (optional, but helpful)
  - The automations will runs tests, update your skill.json file automatically when you push to GitHub, and handle releases with Google's [`release-please`](https://github.com/googleapis/release-please).
- [ ] Update the `locale/en-us/skill.json` file with manual examples and other information you may want. [See the skill.json documentation for details.](https://openvoiceos.github.io/ovos-technical-manual/411-skill_json/)
- [ ] Update the `runtime_requirements` classmethod in `__init__.py` [per the requirements of your skill](https://openvoiceos.github.io/ovos-technical-manual/410-skill_runtime_requirements/)
- [ ] [Think through and design your skill's Voice User Interface VUI](https://openvoiceos.github.io/ovos-technical-manual/400-skill-design-guidelines/)
- [ ] Write your skill code
- [ ] [Write tests for your skill, if you desire](./test/test_skill.py)
- [ ] Document your skill in `README.md`

When you're ready to test your skill in an OVOS environment, install it as you would any other Python package. You can install directly from GitHub with `pip install git+
https://github.com/your-github-username/your-repo-name.git` or by adding your skill to your `requirements.txt` file and running `pip install -r requirements.txt`.

Using `ovos-docker`? See the [ovos-docker documentation](https://openvoiceos.github.io/ovos-docker/getting-started/docker/installation/skills/) for more information on how to add your skill to your Docker container.

## Questions?

Reach out to the [OVOS community on Matrix](https://matrix.to/#/!XFpdtmgyCoPDxOMPpH:matrix.org?via=matrix.org) with any questions you have about developing your skill. We're here to help! You can also post in the [Open Conversational AI community forum](https://community.openconversational.ai/).
