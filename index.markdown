---
layout: default
---
<section class="profile">
    <h1 class="profile-name">Junseung You (유준승)</h1>
    
    <div class="profile-main">
        <div class="profile-info">
            <p class="profile-position">
                Postdoctoral Researcher
                <span class="profile-separator">|</span>
                Expert Research Personnel (전문연구요원)<br>
                <a href="https://ict.snu.ac.kr/">Institute of Computer Technology</a><br>
                <a href="https://www.snu.ac.kr/">Seoul National University</a>
            </p>

            <p class="profile-bio">
                I am a postdoctoral researcher at the Seoul National University (SNU) Institute of Computer Technology, currently serving my mandatory military service as expert research personnel. I earned my Ph.D. from <a href="http://sor.snu.ac.kr">Security Optimization Lab (SOR Lab)</a> in the Department of ECE at SNU, under the supervision of Professor <a href="http://sor.snu.ac.kr/document/ypaek">Yunheung Paek</a>. My research interests include:
            </p>

            <ul class="research-interests" aria-label="Research interests">
                <li>Systems Security</li>
                <li>Autonomous Vehicle Security</li>
                <li>Confidential Computing</li>
                <li>On-device AI Security</li>
            </ul>
        </div>

        <aside class="profile-aside">
            <div class="profile-photo">
                <img
                    src="{{ '/assets/jsyou2.jpeg' | relative_url }}"
                    alt="Portrait of Junseung You">
            </div>

            <nav class="profile-links" aria-label="Professional links">
                <a href="/assets/jsyou.pdf" title="CV" aria-label="CV">
                    <span class="cv-mark" aria-hidden="true">CV</span>
                </a>
                <a href="mailto:jsyou@sor.snu.ac.kr" title="Email" aria-label="Email">
                    <i class="fa-regular fa-envelope" aria-hidden="true"></i>
                </a>
                <a href="https://github.com/junseungyou" title="GitHub" aria-label="GitHub">
                    <i class="fa-brands fa-github" aria-hidden="true"></i>
                </a>
                <a href="https://scholar.google.com/citations?user=hA5MNwcAAAAJ&hl=en" title="Google Scholar" aria-label="Google Scholar">
                    <i class="fa-solid fa-graduation-cap" aria-hidden="true"></i>
                </a>
            </nav>
        </aside>
    </div>
</section>

## News

<div class="news-list">
    <p><strong>Nov 2025</strong> - New paper on securing connected vehicles has been accepted to <em>NDSS 2026</em>.</p>

    <p><strong>May 2025</strong> - New paper on byte-level access control has been accepted to <em>CCS 2025</em>.</p>
</div>

<div class="publications-section">
<input class="publications-toggle" type="checkbox" id="publications-full" aria-label="Show full publication list">
<h2 class="publications-heading">Publications <label for="publications-full">(full)</label></h2>

<div class="publication-list">
    <article class="pub-entry publication-optional">
        <div class="pub-side">
            <div class="pub-venue pub-status">Under submission</div>
        </div>
        
        <div class="pub-body">
            <div class="pub-title">CCAX: Extending Confidential Virtual Machine for Nested Enclaves on ARM</div>
        </div>
    </article>
        
    <article class="pub-entry publication-optional">
        <div class="pub-side">
            <div class="pub-venue pub-status">Under submission</div>
        </div>
        
        <div class="pub-body">
            <div class="pub-title">Hardware-assisted Isolation of Rust from Unsafe Languages on ARM</div>
        </div>
    </article>

<article class="pub-entry">
    <div class="pub-side">
        <div class="pub-venue">NDSS</div>
        
        <div class="pub-links" aria-label="Publication resources">
            <a href="/assets/secv.pdf" title="Paper" aria-label="Paper">
                <i class="fa-regular fa-file-pdf" aria-hidden="true"></i>
            </a>
        </div>
    </div>
    
    <div class="pub-body">
        <div class="pub-title">
            SECV: Securing Connected Vehicles with Hardware Trust Anchors
        </div>
        <div class="pub-authors">
            Martin Kayondo<sup>⭑</sup>, <strong>Junseung You</strong><sup>⭑</sup>, Eunmin Kim, Jiwon Seo, and Yunheung Paek
        </div>
        <div class="pub-conference">
            Network and Distributed System Security Symposium, 2026
        </div>
        <div class="pub-note">
            ⭑ co-first authors
        </div>
    </div>
</article>

<article class="pub-entry">
    <div class="pub-side">
        <div class="pub-venue">CCS</div>
    
        <div class="pub-links" aria-label="Publication resources">
            <a href="/assets/bastag.pdf" title="Paper" aria-label="Paper">
                <i class="fa-regular fa-file-pdf" aria-hidden="true"></i>
            </a>
            
            <a href="/assets/bastag-slides.pdf" title="Slides" aria-label="Slides">
                <i class="fa-regular fa-file-powerpoint" aria-hidden="true"></i>
            </a>
        </div>
    </div>
    
    <div class="pub-body">
        <div class="pub-title">
            BASTAG: Byte-level Access Control on Shared Memory using ARM Memory Tagging Extension
        </div>
        <div class="pub-authors">
            <strong>Junseung You</strong>, Jiwon Seo, Kyeongryong Lee, Yeongpil Cho, and Yunheung Paek
        </div>
        <div class="pub-conference">
            ACM SIGSAC Conference on Computer and Communications Security, 2025
        </div>
    </div>
</article>

<article class="pub-entry">
    <div class="pub-side">
        <div class="pub-venue">SoCC</div>
    
        <div class="pub-links" aria-label="Publication resources">
            <a href="/assets/kvsev.pdf" title="Paper" aria-label="Paper">
                <i class="fa-regular fa-file-pdf" aria-hidden="true"></i>
            </a>
        
            <a href="/assets/kvsev-slides.pdf" title="Slides" aria-label="Slides">
                <i class="fa-regular fa-file-powerpoint" aria-hidden="true"></i>
            </a>
        </div>
    </div>
    
    <div class="pub-body">
        <div class="pub-title">
            KVSEV: A Secure In-Memory Key-Value Store with Secure Encrypted Virtualization
        </div>
        <div class="pub-authors">
            <strong>Junseung You</strong>, Kyeongryong Lee, Hyungon Moon, Yeongpil Cho, and Yunheung Paek
        </div>
        <div class="pub-conference">
            ACM Symposium on Cloud Computing, 2023
        </div>
    </div>
</article>

<article class="pub-entry">
    <div class="pub-side">
        <div class="pub-venue">TIFS</div>
        
        <div class="pub-links" aria-label="Publication resources">
            <a href="/assets/zometag.pdf" title="Paper" aria-label="Paper">
                <i class="fa-regular fa-file-pdf" aria-hidden="true"></i>
            </a>
        </div>
    </div>
    
    <div class="pub-body">
        <div class="pub-title">
            ZOMETAG: Zone-based Memory Tagging for Fast, Deterministic Detection of Spatial Memory Violations on ARM
        </div>
        <div class="pub-authors">
            Jiwon Seo<sup>⭑</sup>, <strong>Junseung You</strong><sup>⭑</sup>, Donghyun Kwon, Yeongpil Cho,  and Yunheung Paek
        </div>
        <div class="pub-conference">
            IEEE Transactions on Information Forensics and Security, 2023
        </div>
        <div class="pub-note">
            ⭑ co-first authors
        </div>
    </div>
</article>

<article class="pub-entry">
    <div class="pub-side">
        <div class="pub-venue">ASIACCS</div>

        <div class="pub-links" aria-label="Publication resources">
            <a href="/assets/sfitag.pdf" title="Paper" aria-label="Paper">
                <i class="fa-regular fa-file-pdf" aria-hidden="true"></i>
            </a>
        </div>
    </div>

    <div class="pub-body">
        <div class="pub-title">
            SFITAG: Efficient Software Fault Isolation with Memory Tagging for ARM Kernel Extensions
        </div>
        <div class="pub-authors">
            Jiwon Seo, <strong>Junseung You</strong>, Yungi Cho, Yeongpil Cho, Donghyun Kwon, and Yunheung Paek
        </div>
        <div class="pub-conference">
            ACM ASIA Conference on Computer and Communications Security, 2023
        </div>
    </div>
</article>

<article class="pub-entry">
    <div class="pub-side">
        <div class="pub-venue">Access</div>

        <div class="pub-links" aria-label="Publication resources">
            <a href="/assets/vatalloc.pdf" title="Paper" aria-label="Paper">
                <i class="fa-regular fa-file-pdf" aria-hidden="true"></i>
            </a>
        </div>
    </div>

    <div class="pub-body">
        <div class="pub-title">
            Enhancing a Lock-and-Key Scheme with MTE to Mitigate Use-After-Frees
        </div>
        <div class="pub-authors">
            Inyoung Bang, Martin Kayondo, <strong>Junseung You</strong>, Donghyun Kwon, Yeongpil Cho, and Yunheung Paek
        </div>
        <div class="pub-conference">
            IEEE Access, 2023
        </div>
    </div>
</article>

<article class="pub-entry">
    <div class="pub-side">
        <div class="pub-venue">Access</div>

        <div class="pub-links" aria-label="Publication resources">
            <a href="/assets/sbgen.pdf" title="Paper" aria-label="Paper">
                <i class="fa-regular fa-file-pdf" aria-hidden="true"></i>
            </a>
        </div>
    </div>

    <div class="pub-body">
        <div class="pub-title">
            SBGen: A Framework to Efficiently Supply Runtime Information for a Learning-based HIDS for Multiple Virtual Machines
        </div>
        <div class="pub-authors">
            Jiwon Seo, Inyoung Bang, <strong>Junseung You</strong>, Yeongpil Cho, and Yunheung Paek
        </div>
        <div class="pub-conference">
            IEEE Access, 2020
        </div>
    </div>
</article>

</div>
</div>


<div class="education-section">
<input class="education-toggle" type="checkbox" id="education-full" aria-label="Show full education history">
<h2 class="education-heading">Education <label for="education-full">(full)</label></h2>

<div class="education-list">
    <div class="education-entry">
        <div><strong>Seoul National University</strong>, Ph.D. in Electrical and Computer Engineering</div>
        <div class="education-date">Sep 2019 – Feb 2026</div>
    </div>

    <div class="education-entry">
        <div><strong>Seoul National University</strong>, B.E. in Electrical and Computer Engineering</div>
        <div class="education-date">Mar 2014 – Aug 2019</div>
    </div>

    <div class="education-entry education-optional">
        <div><strong>Korean Minjok Leadership Academy</strong></div>
        <div class="education-date">Mar 2011 – Feb 2014</div>
    </div>
</div>
</div>

## Experience


## Talks &amp; Seminars

<div class="talk-list">
    <div class="talk-entry">
        <div class="talk-heading">
            <div class="talk-title">A Systematic Look at Mutual Privacy in AI Model Usage</div>
            <div class="talk-date">May 2026</div>
        </div>
        <div class="talk-meta">
            <span>한국정보보호학회(KIISC) 차세대 저작권보호기술 워크숍</span>
            <!-- Replace # with the slides URL. -->
            <a class="talk-slides" href="/assets/seminar_workshop.pdf" title="Slides" aria-label="Slides">
                <i class="fa-regular fa-file-powerpoint" aria-hidden="true"></i>
            </a>
        </div>
    </div>
    
    <div class="talk-entry">
        <div class="talk-heading">
            <div class="talk-title">Hardware-Assisted Security on Arm Mobile Platforms—From Memory Safety to Confidential Computing</div>
            <div class="talk-date">Dec 2025</div>
        </div>
        <div class="talk-meta">
            <span>Pusan National University (online)</span>
        </div>
    </div>
    
    <div class="talk-entry">
        <div class="talk-heading">
            <div class="talk-title">Hardware-Assisted Security on Arm Mobile Platforms—From Memory Safety to Confidential Computing</div>
            <div class="talk-date">Nov 2025</div>
        </div>
        <div class="talk-meta">
            <span>Sejong University</span>
            <!-- Replace # with the slides URL. -->
            <a class="talk-slides" href="/assets/seminar_sejong.pdf" title="Slides" aria-label="Slides">
                <i class="fa-regular fa-file-powerpoint" aria-hidden="true"></i>
            </a>
        </div>
    </div>
</div>

## Services
