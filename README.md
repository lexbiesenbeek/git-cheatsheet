## Picturae Git Flow procedure

### Hotfix

<pre><code>
git flow hotfix start &lt;tagname&gt;
...changes...
git flow hotfix finish &lt;tagname&gt;
git push
git checkout develop
git push
git push --tags
</code></pre>

### Release

<pre><code>
git flow release start &lt;releasename&gt;
...changes...
git flow release finish &lt;releasename&gt;
git push
git checkout develop
git push
git push --tags
</code></pre>

## Show staged files
<code>git diff --name-only --staged</code>
or
<code>git diff --name-only --cached</code>
