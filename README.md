# History and/or Philosophy of Science (HPS) scholars hanging out on Mastodon

This repository (forked from our [STS neighbours (hey!)](https://jwyg.github.io/mastodon-sts/), itself forked from a [list of sociologists](https://www.perspektivbrocken.org/en/2022/10/28/sociologists-on-mastodon-a-list/) {talk about knowledge sharing, ei!}) has a list of self-included History and/or Philosophy of Science (HPS) researchers, broadly construed, with a Mastodon account. Same as in the original repo, you can create a csv-file that can be uploaded in your mastodon settings, in order to follow every account from the list.

Head to [https://oliviodare.github.io/mastodon-hps/](https://oliviodare.github.io/mastodon-hps/) for the finished product.

## Can I use this for my discipline/peer group?

Yes, basically you just have to fork the repo. There are two files that you will need to change. The Text in index.html and the accounts that are stored in resources/hpsers.csv. Please keep the name of this file (or change it in assets/js/createcsv.js, too).

You can publish your web app directly from the repository. For this, go to “Settings” and then choose “pages” in the left menu.

## Documentation

### csv file

the csv file is stored in /resources/.
Any file with the columns: `account`,`name`,`url` will do.

### tootformat.html
The page tootformat.html renders all accounts from the csv as ”account (name)”. This offers you a more readable format which you can copy to your posts in Mastodon.

## License

The repository can be used under GNU General Public License v3, except the /resources/hpsers.csv file, which can only be used with explicit permission by the authors.
