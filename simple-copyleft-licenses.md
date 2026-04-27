# Lightweight copyleft licenses — and the case for SimPL 2.0

> ### TL;DR
> **SimPL 2.0** and **MS-RL** are OSI-approved, SPDX-listed copyleft licenses
> that can be used as a concise and easy-to-read alternative
> to the GPL, the MPL, or other copyleft licenses.

## Background and motivation

Options for [permissive free software licenses][permissive-license] abound,
and include some of the most popular licenses,
ranging from simple and readable ones such as MIT, BSD or ISC,
to longer and more detailed ones like Apache or Artistic.

On the other hand, [reciprocal (copyleft) free software licenses][reciprocal-license]
tend to cluster primarily in the verbose end of the spectrum
— for example, the GNU General Public License (GPL) or the Mozilla Public License (MPL).
This leaves those who want to ensure their software contributes to a protected commons
(i.e. requiring that software that builds upon it is also shared openly on similar terms),
having almost no options for simple, approachable copyleft licenses to use.

This may seem like a frivolous or inconsequential matter,
but the notorious popularity of the MIT license,
as well as the rapid dissemination of the Creative Commons licenses
clearly indicate that there is appetite for straightforward, legible agreements
whose conciseness and clarity provide confidence to both licensors and licensees.

This factor is especially important in the highly distributed open source ecosystem,
whose participants are often hobbyists, and generally discouraged by bureaucracy
such as handling the legal complexities of software licensing.

It is therefore quite a relevant question, for those who prefer a share-alike arrangement,
whether there are licenses providing such terms in clear and readable prose,
as opposed to the legalese-ridden "walls of text" that licenses can often become.

[permissive-license]: https://en.wikipedia.org/wiki/Permissive_software_license
[reciprocal-license]: https://en.wikipedia.org/wiki/Copyleft

## Survey of existing options

There are various proposals for concise licenses of the reciprocal kind
but none of them have garnered significant usage,
and most haven't been included in curated lists of software licenses.

Several such options are licenses proposed by Kyle E. Mitchell,
most notably the [Parity Public License][parity],
but also [Round Robin][round-robin], [Patches Back][patches-back] and [Maximaleft][maximaleft].
There is also the [Libre Source][libre-source],
a derivative of the Patches Back license proposed by Moritz Maxeiner,
which has since been abandoned (as has Patches Back, for that matter).

[parity]: https://paritylicense.com
[round-robin]: https://roundrobinlicense.com
[maximaleft]: https://github.com/berneout/maximaleft
[patches-back]: https://github.com/berneout/patches-back-public-license
[libre-source]: https://github.com/MoritzMaxeiner/libre-source-license

Of these, the Parity is the only one seeing any notable [adoption][parity-usage]
and the only one with an [SPDX identifier](https://spdx.org/licenses/Parity-7.0.0.html);
but it is not recognized by the OSI or the FSF, and neither are any of the others.

[parity-usage]: https://github.com/search?q=%22Parity%20Public%20License%22+path%3A%2F%5E%28licen%5Bcs%5De%7Ccopying%29%28%5C.md%7C%5C.txt%29%3F%24%2F+NOT+is%3Afork+NOT+is%3Aarchived&type=code

Two licenses, however, stand out from the set:

- The Simple Public License 2.0 (SimPL-2.0)
- The Microsoft Reciprocal License (MS-RL)

### Simple Public License 2.0 (SimPL-2.0)

SimPL was originally drafted by Robert W. Gomulkiewicz,
an intellectual property law scholar from the University of Washington School of Law,
in a [2005 paper](https://houstonlawreview.org/article/4788-general-public-license-3-0-hacking-the-free-software-movements-constitution)
published in volume 42, issue 4 of the _Houston Law Review_.

Its own text describes it as a plain-language implementation of GPL 2.0.
That makes it an interesting option for projects that want reciprocity
without having to adopt a complex, lengthy copyleft license.

What makes SimPL especially notable among lightweight copyleft licenses
is that it has been formally [approved by the OSI](https://opensource.org/license/SimPL-2.0).
It also has an [SPDX identifier](https://spdx.org/licenses/SimPL-2.0.html) (`SimPL-2.0`),
and even an [entry at tl;drLegal](https://www.tldrlegal.com/license/simple-public-license-2-0-simpl).

It's worth noting that, despite the SimPL's explicit design goal of matching the terms of GPL 2.0,
the FSF has not explicitly assessed the SimPL in its [list of free licenses][fsf-license-list];
therefore, although it is almost certain to match the FSF's criteria for free software licenses,
and is also likely GPL-compatible, neither conclusion has been confirmed by the FSF yet.

[fsf-license-list]: https://www.gnu.org/licenses/license-list.en.html

### Microsoft Reciprocal License (MS-RL)

The Microsoft Reciprocal License (MS-RL) was introduced by Microsoft in 2007,
as part of the set of licenses it submitted for OSI review.
In the corresponding [discussion][ms-rl-osi] on the OSI license list,
Microsoft explicitly stated that it sought to draft a license that was
"simple, short, and easy-to-understand".

The license has been [approved by the OSI](https://opensource.org/license/ms-rl),
and it also has an [SPDX identifier](https://spdx.org/licenses/MS-RL.html) (`MS-RL`)
and an entry at [tl;drLegal](https://www.tldrlegal.com/license/microsoft-reciprocal-license-ms-rl).

Interestingly (especially in contrast to the SimPL),
the MS-RL has been explicitly [approved as a free license by the FSF][ms-rl-fsf],
though it notes that it is **not** GPL-compatible.

[ms-rl-osi]: https://lists.opensource.org/pipermail/license-discuss_lists.opensource.org/2007-October/014348.html
[ms-rl-fsf]: https://www.gnu.org/licenses/license-list.en.html#ms-rl

### Comparison: SimPL 2.0 vs. MS-RL

#### Side-by-side license text

<table>
<tr>
  <th style="width: 50%;">Simple Public License (SimPL) 2.0</th>
  <th style="width: 50%;">Microsoft Reciprocal License (Ms-RL)</th>
</tr>
<tr><td style="vertical-align: top;">

  <p>
    The SimPL applies to the software's source and object code
    and comes with any rights that I have in it (other than trademarks).
    You agree to the SimPL by copying, distributing, or making a derivative work of the software.
  </p>

  <p>You get the royalty free right to:</p>
  <ul>
    <li>Use the software for any purpose;</li>
    <li>Make derivative works of it (this is called a "Derived Work");</li>
    <li>Copy and distribute it and any Derived Work.</li>
  </ul>

  <p>If you distribute the software or a Derived Work, you must give back to the community by:</p>
  <ul>
    <li>
      Prominently noting the date of any changes you make;
    </li><li>
      Leaving other people's copyright notices, warranty disclaimers, and license terms in place;
    </li><li>
      Providing the source code, build scripts, installation scripts, and interface definitions
      in a form that is easy to get and best to modify;
    </li><li>
      Licensing it to everyone under SimPL, or substantially similar terms (such as GPL 2.0),
      without adding further restrictions to the rights provided;
    </li><li>
      Conspicuously announcing that it is available under that license.
    </li>
  </ul>

  <p>There are some things that you must shoulder:</p>
  <ul>
    <li>You get NO WARRANTIES. None of any kind;</li>
    <li>
      If the software damages you in any way, you may only recover direct damages
      up to the amount you paid for it (that is zero if you did not pay anything).
      You may not recover any other damages, including those called "consequential damages".
      (The state or country where you live may not allow you to limit your liability in this way,
      so this may not apply to you);
    </li>
  </ul>

  <p>The SimPL continues perpetually, except that your license rights end automatically if:</p>
  <ul>
    <li>
      You do not abide by the "give back to the community" terms
      (your licensees get to keep their rights if they abide);
    </li>
    <li>Anyone prevents you from distributing the software under the terms of the SimPL.</li>
  </ul>

</td><td style="vertical-align: top;">

  <p>
    This license governs use of the accompanying software.
    If you use the software, you accept this license.
    If you do not accept the license, do not use the software.
  </p>

  <ol style="padding-left: 1em;">
    <li>
      <p>Definitions</p>
      <ul style="list-style-type: disc; padding-left: 1em;">
        <li>
          The terms "reproduce," "reproduction," "derivative works," and "distribution"
          have the same meaning here as under U.S. copyright law.
        </li><li>
          A "contribution" is the original software, or any additions or changes to the software.
        </li><li>
          A "contributor" is any person that distributes its contribution under this license.
        </li><li>
          "Licensed patents" are a contributor's patent claims that read directly on its contribution.
        </li>
      </ul>
    </li>
    <li>
      <p>Grant of Rights</p>
      <ol style="list-style-type: upper-alpha; padding-left: 1em;">
          <li>
            <i>Copyright Grant-</i>
            Subject to the terms of this license, including the license conditions and limitations in section 3,
            each contributor grants you a non-exclusive, worldwide, royalty-free copyright license
            to reproduce its contribution, prepare derivative works of its contribution, and distribute
            its contribution or any derivative works that you create.
          </li><li>
            <i>Patent Grant-</i>
            Subject to the terms of this license, including the license conditions and limitations in section 3,
            each contributor grants you a non-exclusive, worldwide, royalty-free license under its licensed patents
            to make, have made, use, sell, offer for sale, import, and/or otherwise dispose of
            its contribution in the software or derivative works of the contribution in the software.
          </li>
      </ol>
    </li>
    <li>
      <p>Conditions and Limitations</p>
      <ol style="list-style-type: upper-alpha; padding-left: 1em;">
        <li>
          <i>Reciprocal Grants-</i>
          For any file you distribute that contains code from the software (in source code or binary format),
          you must provide recipients the source code to that file along with a copy of this license,
          which license will govern that file.
          You may license other files that are entirely your own work
          and do not contain code from the software under any terms you choose.
        </li><li>
          <i>No Trademark License-</i>
          This license does not grant you rights to use any contributors' name, logo, or trademarks.
        </li><li>
          If you bring a patent claim against any contributor over patents that you claim are infringed by the software,
          your patent license from such contributor to the software ends automatically.
        </li><li>
          If you distribute any portion of the software,
          you must retain all copyright, patent, trademark, and attribution notices
          that are present in the software.
        </li><li>
          If you distribute any portion of the software in source code form,
          you may do so only under this license by including a complete copy of this license with your distribution.
          If you distribute any portion of the software in compiled or object code form,
          you may only do so under a license that complies with this license.
        </li><li>
          The software is licensed "as-is." You bear the risk of using it.
          The contributors give no express warranties, guarantees, or conditions.
          You may have additional consumer rights under your local laws which this license cannot change.
          To the extent permitted under your local laws, the contributors exclude the implied warranties
          of merchantability, fitness for a particular purpose and non-infringement.
        </li>
      </ol>
    </li>
  </ol>

</td></tr>
</table>

#### Key differences

While this is not legal advice, it is worth pointing out that
the SimPL may have some advantages over the MS-RL; specifically:

1. It is a [strong copyleft license][strong-copyleft].
2. It was published by a copyright law scholar in a reputable, peer-reviewed, law journal.
3. It is shorter than the MS-RL (~1/3 shorter, at 311 words vs. 471 words).
4. It is aligned with the Free Software Foundation's GPL.
5. It is not associated with Microsoft :)

The relevance of points 4 and 5 is naturally subjective,
and for some people the preference may even be inverted,
so feel free to ignore them.
Points 2 and 3, while being arguably somewhat minor,
are nevertheless valid arguments in favor of the SimPL.

Point 1 is perhaps the most important for someone making a choice between the two:
MS-RL differs from SimPL in that its reciprocity (share-alike) requirements
apply only to individual files of the derivative work (clause 3.A),
i.e. only those that contain code from the covered software,
as opposed to the derivative work as a whole.

This makes MS-RL closer in effect to file-level copyleft licenses like the MPL
— an arrangement sometimes called "weak copyleft",
as it protects against "proprietization" of the licensed software,
but does not prevent it from being incorporated into a larger proprietary system,
e.g. as a library included into end-user programs.

Conversely, the SimPL is more akin to the full reciprocity associated with the GPL,
whereas only projects that are fully licensed under similarly open terms
can incorporate software under the SimPL.
These are often called "strong copyleft" (or, sometimes pejoratively, "viral") licenses.

Still, both options further the goals of the copyleft principle
—i.e. ensuring that the free software ecosystem remains open and growing—
so either of them can be used to promote simple, approachable copyleft licensing,
depending on the individual preferences.

[strong-copyleft]: https://en.wikipedia.org/wiki/Copyleft#Strong_and_weak_copyleft

## Conclusion

Based on the discussion above, it can be concluded that
**SimPL 2.0 and MS-RL are viable options for concise, layman-friendly reciprocal licenses**,
featuring institutional recognition and established ecosystem metadata,
and thus filling the gap of a simple, readable alternative to copyleft licenses
such as the GPL or the MPL.

In other words, **SimPL and MS-RL are the copyleft analogs to short permissive licenses like the MIT or BSD**.

## How to use SimPL or MS-RL in a software project

If you're convinced and want to start using these licenses in your projects,
you can do it as usual, by placing the full license text in a root-level file,
using any of the [standard license filenames][license-filenames]
— e.g. `LICENSE`, `LICENSE.md`, `LICENSE.txt`, `COPYING.txt`, etc.

You'll probably also want to use the corresponding SPDX identifier (`SimPL-2.0` or `MS-RL`)
in metadata or package manifest files like `package.json`, `Cargo.toml`, or `pyproject.toml`.

Finally, it can be helpful to mention the licensing choice explicitly in the README,
especially since that can contribute to popularizing these licenses,
by making them more visible and thus leading more people to learn about them.

[license-filenames]: https://reuse.software/spec-1.2/#1-provide-the-exact-text-of-each-license-used
