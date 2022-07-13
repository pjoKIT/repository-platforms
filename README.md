# Overview of Existing (Metadata) Repository Platforms

Source of a living document/website about (metadata) repository platforms and their features.

If you are looking for a repository which provides support for a specific schema only, you might take a look at the Metadata Standards Catalogs:

- https://msc.datamanager.kit.edu
- https://rdamsc.bath.ac.uk

There you might find a repository tailored for your specific needs.

## Adding Content to the document
If you want to add a new metadata repository to the document please do the following:
1. Go to https://github.com/kit-data-manager/repository-platforms and fork the repository.
2. Clone the repo
```
> git clone https://github.com/YOUR_ACCOUNT/repository-platforms
```
3. Copy the template directory to src and rename it.
```
> cd repository-platforms
repository-platforms> cp -R template src/NEW_ENTRY
```
4. Edit all files with a editor of your choice.
5. Add entries to 'src/SUMMARY.md'.
**Note:** You should use alpabetic order.
```
SUMMARY.md:
[...]

- [NEW_ENTRY](NEW_ENTRY/singlePage.md)
   - [Features](NEW_ENTRY/features.md)
   - [Addtional Features](NEW_ENTRY/additionalFeatures.md)
   - [Remarks](NEW_ENTRY/remarks.md)

[...]
```

6. Check results.
Use [mdbook](https://github.com/rust-lang/mdBook/releases) to check the result.
```
metadataRepos> mdbook serve .
```
Open your Browser at: [http://localhost:3000](http://localhost:3000)

If everything looks fine:

7. Make a pull request

Open your Browser at: [https://github.com/YOUR_ACCOUNT/repository-platforms](https://github.com/YOUR_ACCOUNT/repository-platforms)

8. You're done

Wait for the feedback of the administrator. If everything is OK, your entry will be merged and should be online afterwards.
