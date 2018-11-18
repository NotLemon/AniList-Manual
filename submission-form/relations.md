# Relations

This section allows you to set the relation of works compared to others in the same series or universe.

![Relations page for the &apos;Kono Subarashii Sekai ni Shukufuku wo!&apos; anime](../.gitbook/assets/relations_page.png)

{% hint style="warning" %}
Relations should be in _**chronological**_ order.  
Examples: [Bakemonogatari, ](http://anilist.co/anime/5081/Bakemonogatari)[Fate Stay/Night](https://anilist.co/anime/356/Fatestay-night/)
{% endhint %}

## Opposite Relations

When a _prequel, sequel, alternative, character, compilation, contains, source, or adaptation_ relation is added, the corresponding reverse relation will be automatically added to the affected entry.

Example 1 \(Adaptations\):

> The light novel [Kono Subarashii Sekai ni Shukufuku wo!](https://anilist.co/manga/86238/)[ ](https://anilist.co/manga/86238/Kono-Subarashii-Sekai-ni-Shukufuku-wo/)was announced to have both [manga](https://anilist.co/manga/85702/Kono-Subarashii-Sekai-ni-Shukufuku-wo/) and [anime](https://anilist.co/anime/21202/Kono-Subarashii-Sekai-ni-Shukufuku-wo/) adaptations:  
>   
> Adding the [novel](https://anilist.co/manga/86238/Kono-Subarashii-Sekai-ni-Shukufuku-wo/) as the '**source**' to both the [manga](https://anilist.co/manga/85702/Kono-Subarashii-Sekai-ni-Shukufuku-wo/) and [anime](https://anilist.co/anime/21202/Kono-Subarashii-Sekai-ni-Shukufuku-wo/) automatically adds the [manga](https://anilist.co/manga/85702/Kono-Subarashii-Sekai-ni-Shukufuku-wo/) and [anime](https://anilist.co/anime/21202/Kono-Subarashii-Sekai-ni-Shukufuku-wo/) as the '**adaptation**' to the [novel](https://anilist.co/manga/86238/Kono-Subarashii-Sekai-ni-Shukufuku-wo/), and vice versa.

Example 2 \(Sequels\):

> The anime [City Hunter](https://anilist.co/anime/1470/City-Hunter/) had a second season released:  
>   
> Adding [City Hunter 2](https://anilist.co/anime/1471/City-Hunter-2/) as the '**sequel'** to [City Hunter](https://anilist.co/anime/1470/City-Hunter/) automatically adds [City Hunter](https://anilist.co/anime/1470/City-Hunter/) as the '**prequel'** to [City Hunter 2](https://anilist.co/anime/1471/City-Hunter-2/), and vice versa.

Example 3 \(Compilations\):

> The now-defunct magazine, _Pure Yuri Anthology Hirari_, which solely published one-shots, released an anthology containing a selection of six of their one-shots:
>
> Adding [Isshun no Asterism](https://anilist.co/manga/104980) \(one-shot\) _\*\*\_to_ [_Shuuden ni wa Kaeshimasu_](https://anilist.co/manga/85662/Shuuden-ni-wa-Kaeshimasu/) _\(anthology\) with the '_**contains'** _relation automatically adds_ [_Shuuden ni wa Kaeshimasu_](https://anilist.co/manga/85662/Shuuden-ni-wa-Kaeshimasu/) _as the '_**compilation'**\_ to [Isshun no Asterism](https://anilist.co/manga/104980), and vice versa.

## Parent Relations

When updating all other relations \(_spin off, side story, character, summary,_ etc.\) you have to do so from the '_**parent'**_ entry. The parent relation will then be created on the other entry as the opposite.

Example:

> The light novel [Kono Subarashii Sekai ni Shukufuku wo!](https://anilist.co/manga/86238/) had the manga spin-off [Kono Subarashii Sekai ni Bakuen wo!](https://anilist.co/manga/100147/Kono-Subarashii-Sekai-ni-Bakuen-wo/) announced:
>
> To link the entries, you must be in the light novel entry and set [Kono Subarashii Sekai ni Bakuen wo!](https://anilist.co/manga/100147/Kono-Subarashii-Sekai-ni-Bakuen-wo/) as a '**spin-off'**. The '**parent'** relation will then be set in the opposite direction back to the light novel.

{% hint style="warning" %}
[One-shots](../before-you-begin/written-media-information/one-shots.md) that are adapted into a proper serialization are linked through the '**alternative'** relation. The [source](general/typings/source.md) would remain 'original'
{% endhint %}

## Branching

Relations should always branch off the first publication of a series if the series has multiple formats, unless it is clear that a spin-off or adaptation is clearly branched off from a later format.

Example:

> The light novel [Mushoku Tensei: Isekai Ittara Honki Dasu](https://anilist.co/manga/85470/Mushoku-Tensei-Isekai-Ittara-Honki-Dasu/) was serialized in January 2014, and had a manga release, [Mushoku Tensei: Isekai Ittara Honki Dasu](https://anilist.co/manga/85564/Mushoku-Tensei-Isekai-Ittara-Honki-Dasu/), in May 2014, which is linked through the '**adaptation**' relation.  
>   
> Two spin-offs, [Mushoku Tensei - Roxy datte Honki desu](https://anilist.co/manga/104724/Mushoku-Tensei--Roxy-datte-Honki-desu/) and [Mushoku Tensei: 4-koma ni Natte mo Honki Dasu](https://anilist.co/manga/104856/Mushoku-Tensei-4koma-ni-Natte-mo-Honki-Dasu/), were then serialized in December 2017 and October 2018 respectively. Both spin-offs only branch off the light novel, and _**not**_ the manga, so are only be linked to the light novel.

## Relation Table

| Relation | Opposite | Usage |
| :--- | :--- | :--- |
| Source | _Adaptation_ | The original source of an adaptation. |
| Adaptation | _Source_ | A work adapted into a new format. |
| Prequel | _Sequel_ | A story preceding the current work \(chronologically\). |
| Sequel | _Prequel_ | A story succeeding the current work \(chronologically\). |
| Character | _Character_ | A work only related by containing the same character\(s\). |
| Alternative | _Alternative_ | An alternative version. \(Not a straight adaptation\) |
| Contains | _Compilation_ | A singular work  \(eg. one-shot\) |
| Compilation | _Contains_ | A compilation of separate works \(eg. one-shot anthologies\) |
| Side Story | _Parent_ | Often a supplemental work. |
| Spin Off | _Parent_ | A work deviated from the main series. |
| Summary | _Parent_ | A summary of a parent work. |
| Other | _Parent_ | Please refrain from using this option as much as possible, and only when the work definitely does not relate in any other form or the relation is presently unknown. |
| Parent |  | The tree for side stories, characters, summaries, spin off’s, etc. \(cannot be manually set\). |

