# Gogglesbyme

!name: Wikiprojects only
!description: Removes all none wikiprojects
!public: true
!author: Gerard36457

$discard
$boost=2,site=en.wikipedia.org
$boost,site=de.wikipedia.org
$boost,site=wikidata.org
$boost,site=meta.wikimedia.org
$boost=2,site=commons.wikimedia.org
$boost=2,site=en.wiktionary.org
$boost,site=en.wikisource.org
$boost,site=en.wikiversity.org
$boost,site=en.wikibooks.org
$boost,site=en.wikiquote.org
$boost,site=en.wikinews.org
$boost=3,site=species.wikimedia.org
$boost=2,site=wikileaks.org
$boost,site=en.wikijunior.org
$boost,site=en.wikivoyage.org
$boost,site=en.wikinews.org
