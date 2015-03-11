---
title:  Real Data and Requirements
---

### Real Data ###

To improve our digital preservation tools, we need to be able to test them and evaluate of their performance. Publicly available sample files make this much easier. Tool developers can use them to test their work, discover bugs, and hone their tools ready for others to use. A test corpus can contain real digital objects from a collection, or be created specifically for exhibiting certain characteristics for testing purposes. Real data, particularly with examples of broken, badly formed or corrupted files can be particularly useful.

Note that OPF also has it's own [corpora page](http://openpreservation.org/technology/corpora/).

#### Multi-format Corpora ####

* The [OPF Format Corpus](http://openpreservation.org/technology/corpora/opf-format-corpus/) (format report [here](http://opf-labs.org/format-corpus/tools/coverage/reports/))
* The [iPres System Showcase Test Suite](http://www.webarchive.org.uk/datasets/ipres.ds.1/)
* The [Encyclopedia of Graphics File Formats Companion CD-ROM](https://archive.org/details/EncyclopediaOfGraphicsFileFormatsCompanionCd-rom) contains lots of test files for image formats:
    * [EGFF ISO Image](https://archive.org/download/EncyclopediaOfGraphicsFileFormatsCompanionCd-rom/GFF_CD.ISO)
* [EDRM Data Set Files](http://www.edrm.net/projects/dataset/data-set-files)
    * [EDRM File Formats Data Set 1.0.1](http://www.edrm.net/download/all_projects/data_set/EDRM_Data-Set_File-Formats_1-0.zip)
    * [EDRM Internationalization Data Set](http://www.edrm.net/download/all_projects/data_set/EDRM_Data-Set_I18N_1-0.zip)
* [Digital Corpora's](http://digitalcorpora.org/) [corpora](http://digitalcorpora.org/corpora/)
    * Including [govdocs1](http://digitalcorpora.org/corpora/govdocs), also described [here](http://openpreservation.org/technology/corpora/govdocs/)
    * OPF have also created a [by-format subset of govdocs1](http://openpreservation.org/technology/corpora/govdocs-selected/), which you can read more about [here](openpreservation.org/technology/corpora/govdocs-selected/)
* [The Skeleton Test Suite](https://github.com/exponential-decay/skeleton-test-suite) builds test files from PRONOM binary and container signatures. These can be used to test DROID and other (compatible) identification tools. 
* [Fine Free File Test Suite](https://fedorahosted.org/file-tests/) set up for Fedora testing
* [JHOVE's test files](http://jhove.cvs.sourceforge.net/viewvc/jhove/jhove/examples/)
* [JHOVE2's test files](https://bitbucket.org/jhove2/main/src/14e8a6102f63/src/test/resources/examples/)
* The [disktype test files](http://disktype.cvs.sourceforge.net/viewvc/disktype/file-system-sampler/)
* The [Metadata Working Group specifications](http://www.metadataworkinggroup.org/specs/) and [embedded image metadata test corpus](http://www.metadataworkinggroup.org/specs/test_files.html)
* [Apache Tika issue about setting up a nightly test corpus](https://issues.apache.org/jira/browse/TIKA-1302), see also [tika-parsers/src/test/resources/test-documents](http://svn.apache.org/repos/asf/tika/trunk/tika-parsers/src/test/resources/test-documents/)
* [The Chemical MIME Home Page](http://www.ch.ic.ac.uk/chemime/)

#### Format-specific Corpora ####

* PDF:
    * [Adobe Acrobat Engineering](http://acroeng.adobe.com/wp/) site has lots of useful [test documents](http://acroeng.adobe.com/wp/?page_id=10).
    * [Isartor PDF/A Test Suite](http://www.pdfa.org/2011/08/isartor-test-suite/)
* ePub:
    * [The IDPF ePub test suite](https://github.com/IDPF/epub-testsuite)
    * [KBNLresearch/epubPolicyTests](https://github.com/KBNLresearch/epubPolicyTests) - Some #epub samples with encryption, DTBook content and foreign resources, with corresponding #epubcheck output.
* TIFF:
    * The libtiff [TIFF Test Images](http://www.remotesensing.org/libtiff/images.html)
* JP2:
    * [OPF JP2k test corpus](https://github.com/openpreserve/format-corpus/tree/master/jp2k-test)
    * [NITF version 2.1 JPEG 2000 Sample Imagery](http://www.gwg.nga.mil/ntb/baseline/software/testfile/Jpeg2000/index.htm)
    * [JPEG 2000 Part 4 Conformance Test Files](http://web.archive.org/web/20080510121012/http://www.crc.ricoh.com/~gormish/jpeg2000conformance/) (v.1.5 with earlier versions also available in the archive history)
* WARC/ARC:
    * [Internet Archive's Example ARC and WARC files](https://archive.org/details/ExampleArcAndWarcFiles) 


#### Building Corpora ####

If the existing corpora aren't cutting it, perhaps you can contribute to the [OPF Format Corpus](http://openpreservation.org/technology/corpora/opf-format-corpus/) ([hosted on GitHub](https://github.com/openpreserve/format-corpus)). There's a [guide here on how to contribute](http://wiki.curatecamp.org/index.php/Collecting_format_ID_test_files) or you can [contact OPF](http://openpreservation.org/about/contact/) for help on how to get involved.


### Real Requirements ###

To develop and use the right tools, we need a deep understanding of our digital preservation requirements. You can learn and share more at the [DP Requirements and Solutions wiki](http://wiki.opf-labs.org/display/REQ/Digital+Preservation+and+Data+Curation+Requirements+and+Solutions).

