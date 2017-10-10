On this page, you can configure the import. What exactly your options are depends on two things:

- Your progress throughout the configuration (it can be multiple steps);
- The type of file you have uploaded.

**Basic CSV import options**

- The date format can be difficult. See examples and options on [this page](https://secure.php.net/manual/en/datetime.createfromformat.php#refsect1-datetime.createfromformat-parameters).
- The field delimiter is not easily visible in Excel, Numbers or Open/LibreOffice. Use a text editor.
- The default import account is an absolute fallback, so use your main account.
- The checkboxes at the bottom of the page are only relevant for the specified banks.

**Define column roles**

Firefly III cannot guess what data each column contains. You must tell Firefly which kinds of data to expect.

The example data can guide you into picking the correct type from the dropdown. If a column cannot be matched to a useful data type, please let me know [by creating an issue](https://github.com/JC5/firefly-iii/issues/new).

About "map these values":

Mapping is meant to connect values from your file, to actual entries in your database. Take a look at these two example accounts:

- ALBERT_HE_1246
- AH_TO_GO_UTR_CS

Both should be linked to my "Albert Heijn"-account. I check "Map these values" so in the next step, I can link them.

So, some values in your CSV file, such as account names or categories, may already exist in your Firefly III database. If you select "map these values" Firefly will not attempt to search for matching values itself but allow you to match the CSV values against the values in your database. This allows you to fine-tune the import.

**Connect import data to Firefly III data**

Here you can do the actual mapping, if you have opted to map data in the previous step. If you select "(do not map)" nothing will be mapped.