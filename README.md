StorylineJS is a prototype tool to make it easy to provide a narrative contect for timeseries data.

ROADMAP
-------
In our current cycle (ending mid-March 2017), we are trying to get a prototype which can be tested in a browser with a variety of datasets. We want to find the edge cases that test the design concepts developed in the Fall 2016 Knight Lab Studio Class and identify any hard challenges in presentation.

If this prototype is promising, we'll consider also developing an authoring tool to make it easier for people to create embeddable storylines.

DEVELOPING
----------
After checking out the repository, run

    npm install
    npm run start

This should get you a locally running webserver which supports viewing a sample storyline and which supports automatic recompilation as code changes.

AUTHORING
---------
In this stage of StorylineJS's development, you must write some javascript, including your own configuration file. Here are the details.

Much like our other tools, you instantiate a storyline with two arguments: the ID of a DOM element which will contain the rendered storyline, and a configuration object which provides the details.

```
  <script src="https://cdn.knightlab.com/libs/storyline/latest/js/storyline.js"></script>
  <link rel="stylesheet" href="https://cdn.knightlab.com/libs/storyline/latest/css/storyline.css">
  var storyline = new Storyline('my-storyline', config);
```
