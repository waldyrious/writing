# There's a MIT-sized copyleft license — and more people should be using it

> ### TL;DR
> **SimPL 2.0** and **MS-RL** are robust, vetted copyleft licenses
> short enough to fit on a single page —the share-alike equivalents of MIT and BSD—
> yet most developers have never heard of them.

## Background and motivation

Many developers choose to release their software
under a [copyleft (share-alike) license][reciprocal-license],
to ensure that any software building upon it must also be shared openly on similar terms,
thus actively contributing to the [digital commons][digital-commons].

However, the most well-known options for copyleft licenses,
such as the GNU General Public License (GPL) or the Mozilla Public License (MPL),
tend to be relatively long and complex documents.
This can make their use less appealing,
as both users and maintainers of free software (who are normally not legal experts)
may feel uncertain whether they fully understand what they're agreeing to.

This is in stark contrast to the [permissive][permissive-license]
side of open source, where short and readable licenses like MIT, BSD, and ISC
have flourished alongside longer and more detailed ones like Apache or Artistic.

The remarkable popularity of the MIT license,
as well as the rapid dissemination of the Creative Commons licenses,
clearly indicate that there is appetite for straightforward, legible agreements
whose conciseness and clarity provide confidence to both licensors and licensees.

That appetite is equally present among developers who prefer share-alike terms,
but it is underserved by current well-known copyleft licenses.
This doesn't have to be the case, as shown below.

[permissive-license]: https://en.wikipedia.org/wiki/Permissive_software_license
[reciprocal-license]: https://en.wikipedia.org/wiki/Copyleft
[digital-commons]: https://en.wikipedia.org/wiki/Digital_commons

## Survey of existing options

A few proposals for concise, readable copyleft licenses have been put forth,
but they tend to lack institutional recognition
(from the OSI, FSF, and in many cases even an SPDX identifier)
and have generally not achieved broad adoption.
A notable example is Kyle E. Mitchell's [Parity Public License](https://paritylicense.com),
among others like [Round Robin](https://roundrobinlicense.com),
[Patches Back](https://github.com/berneout/patches-back-public-license),
[Maximaleft](https://github.com/berneout/maximaleft) and
[Libre Source](https://github.com/MoritzMaxeiner/libre-source-license).

Two licenses, however, stand out from this set:

- The Simple Public License 2.0 (SimPL-2.0)
- The Microsoft Reciprocal License (MS-RL)

### Simple Public License 2.0 (SimPL-2.0)

SimPL was originally drafted by Robert W. Gomulkiewicz,
an intellectual property law scholar from the University of Washington School of Law,
and published in a [2005 paper in the Houston Law Review][hous-law-rev-2025].

Its own text describes it as a plain-language implementation of GPL 2.0.
That makes it an interesting option for projects that want reciprocity
without having to adopt a complex, lengthy copyleft license.

What makes SimPL especially notable among lightweight copyleft licenses
is that it has been formally [approved by the OSI](https://opensource.org/license/SimPL-2.0).
It also has an [SPDX identifier](https://spdx.org/licenses/SimPL-2.0.html) (`SimPL-2.0`),
and even an [entry at tl;drLegal](https://www.tldrlegal.com/license/simple-public-license-2-0-simpl).

Given that SimPL was written with the explicit goal of matching the terms of GPL 2.0,
it complies by design with the FSF's criteria for free software licenses,
and is therefore likely GPL-compatible
— though the FSF has not yet [declared that explicitly][fsf-license-list].

[hous-law-rev-2025]: https://houstonlawreview.org/article/4788-general-public-license-3-0-hacking-the-free-software-movements-constitution
[fsf-license-list]: https://www.gnu.org/licenses/license-list.en.html

### Microsoft Reciprocal License (MS-RL)

The Microsoft Reciprocal License (MS-RL) was introduced by Microsoft in 2007,
as part of the set of licenses it submitted for OSI review.
In the corresponding [discussion][ms-rl-osi] on the OSI license list,
Microsoft explicitly stated that it sought to draft a license that was
"simple, short, and easy-to-understand".

Like the SimPL 2.0, MS-RL is [approved by the OSI](https://opensource.org/license/ms-rl),
has a registered [SPDX identifier](https://spdx.org/licenses/MS-RL.html) (`MS-RL`)
and an entry at [tl;drLegal](https://www.tldrlegal.com/license/microsoft-reciprocal-license-ms-rl).

Interestingly (especially in contrast to the SimPL),
the MS-RL has been explicitly [approved as a free license by the FSF][ms-rl-fsf],
though it notes that it is **not** GPL-compatible.

[ms-rl-osi]: https://lists.opensource.org/pipermail/license-discuss_lists.opensource.org/2007-October/014348.html
[ms-rl-fsf]: https://www.gnu.org/licenses/license-list.en.html#ms-rl

### Comparison: SimPL 2.0 vs. MS-RL

#### Side-by-side license text

<table style="width: clamp(100%, 80vw, 140em); position: relative; left: 50%; transform: translate(-50%); border-collapse: separate; border-spacing: 0.5em 0;">
<tr><td style="width: 50%; vertical-align: top; background: #f9f9f0; line-height: 1.25;">

  <h5 style="text-align: center;">Simple Public License (SimPL) 2.0</h5>

  <p>
    The SimPL applies to the software's source and object code
    and comes with any rights that I have in it (other than trademarks).
    You agree to the SimPL by copying, distributing, or making a derivative work of the software.
  </p>

  <p>You get the royalty free right to:</p>
  <ul>
    <li>Use the software for any purpose;</li>
    <li>Make derivative works of it (this is called a "Derived Work");</li>
    <li>Copy and distribute it and any Derived Work.</li>
  </ul>

  <p>If you distribute the software or a Derived Work, you must give back to the community by:</p>
  <ul>
    <li>
      Prominently noting the date of any changes you make;
    </li><li>
      Leaving other people's copyright notices, warranty disclaimers, and license terms in place;
    </li><li>
      Providing the source code, build scripts, installation scripts, and interface definitions
      in a form that is easy to get and best to modify;
    </li><li>
      Licensing it to everyone under SimPL, or substantially similar terms (such as GPL 2.0),
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

</td><td style="width: 50%; vertical-align: top; background: #f9f9f0; line-height: 1.25;">

  <h5 style="text-align: center;">Microsoft Reciprocal License (Ms-RL)</h5>

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
            <i>Copyright Grant -</i>
            Subject to the terms of this license, including the license conditions and limitations in section 3,
            each contributor grants you a non-exclusive, worldwide, royalty-free copyright license
            to reproduce its contribution, prepare derivative works of its contribution, and distribute
            its contribution or any derivative works that you create.
          </li><li>
            <i>Patent Grant -</i>
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
          <i>Reciprocal Grants -</i>
          For any file you distribute that contains code from the software (in source code or binary format),
          you must provide recipients the source code to that file along with a copy of this license,
          which license will govern that file.
          You may license other files that are entirely your own work
          and do not contain code from the software under any terms you choose.
        </li><li>
          <i>No Trademark License -</i>
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
