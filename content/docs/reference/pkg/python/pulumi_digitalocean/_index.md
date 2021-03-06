---
title: Package pulumi_digitalocean
title_tag: Package pulumi_digitalocean | Python SDK
linktitle: pulumi_digitalocean
notitle: true
---

<div class="section" id="pulumi-digitalocean">
<h1>Pulumi DigitalOcean<a class="headerlink" href="#pulumi-digitalocean" title="Permalink to this headline">¶</a></h1>
<blockquote>
<div><p>This provider is a derived work of the <a class="reference external" href="https://github.com/terraform-providers/terraform-provider-digitalocean">Terraform Provider</a> distributed under
<a class="reference external" href="https://www.mozilla.org/en-US/MPL/2.0/">MPL 2.0</a>. If you encounter a bug or missing feature, first check the
<a class="reference external" href="https://github.com/pulumi/pulumi-digitalocean/issues">pulumi/pulumi-digitalocean repo</a>; however, if that doesn’t turn up
anything, please consult the source <a class="reference external" href="https://github.com/terraform-providers/terraform-provider-digitalocean/issues">terraform-providers/terraform-provider-digitalocean repo</a>.</p>
</div></blockquote>
<span class="target" id="module-pulumi_digitalocean"></span><dl class="py class">
<dt id="pulumi_digitalocean.AwaitableGetAccountResult">
<em class="property">class </em><code class="sig-prename descclassname">pulumi_digitalocean.</code><code class="sig-name descname">AwaitableGetAccountResult</code><span class="sig-paren">(</span><em class="sig-param"><span class="n">droplet_limit</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">email</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">email_verified</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">floating_ip_limit</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">id</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">status</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">status_message</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">uuid</span><span class="o">=</span><span class="default_value">None</span></em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_digitalocean.AwaitableGetAccountResult" title="Permalink to this definition">¶</a></dt>
<dd></dd></dl>

<dl class="py class">
<dt id="pulumi_digitalocean.AwaitableGetCertificateResult">
<em class="property">class </em><code class="sig-prename descclassname">pulumi_digitalocean.</code><code class="sig-name descname">AwaitableGetCertificateResult</code><span class="sig-paren">(</span><em class="sig-param"><span class="n">domains</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">id</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">name</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">not_after</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">sha1_fingerprint</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">state</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">type</span><span class="o">=</span><span class="default_value">None</span></em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_digitalocean.AwaitableGetCertificateResult" title="Permalink to this definition">¶</a></dt>
<dd></dd></dl>

<dl class="py class">
<dt id="pulumi_digitalocean.AwaitableGetDatabaseClusterResult">
<em class="property">class </em><code class="sig-prename descclassname">pulumi_digitalocean.</code><code class="sig-name descname">AwaitableGetDatabaseClusterResult</code><span class="sig-paren">(</span><em class="sig-param"><span class="n">database</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">engine</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">host</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">id</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">maintenance_windows</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">name</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">node_count</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">password</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">port</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">private_host</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">private_network_uuid</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">private_uri</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">region</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">size</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">tags</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">uri</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">urn</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">user</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">version</span><span class="o">=</span><span class="default_value">None</span></em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_digitalocean.AwaitableGetDatabaseClusterResult" title="Permalink to this definition">¶</a></dt>
<dd></dd></dl>

<dl class="py class">
<dt id="pulumi_digitalocean.AwaitableGetDomainResult">
<em class="property">class </em><code class="sig-prename descclassname">pulumi_digitalocean.</code><code class="sig-name descname">AwaitableGetDomainResult</code><span class="sig-paren">(</span><em class="sig-param"><span class="n">id</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">name</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">ttl</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">urn</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">zone_file</span><span class="o">=</span><span class="default_value">None</span></em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_digitalocean.AwaitableGetDomainResult" title="Permalink to this definition">¶</a></dt>
<dd></dd></dl>

<dl class="py class">
<dt id="pulumi_digitalocean.AwaitableGetDropletResult">
<em class="property">class </em><code class="sig-prename descclassname">pulumi_digitalocean.</code><code class="sig-name descname">AwaitableGetDropletResult</code><span class="sig-paren">(</span><em class="sig-param"><span class="n">backups</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">created_at</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">disk</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">id</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">image</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">ipv4_address</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">ipv4_address_private</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">ipv6</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">ipv6_address</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">ipv6_address_private</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">locked</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">memory</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">monitoring</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">name</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">price_hourly</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">price_monthly</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">private_networking</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">region</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">size</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">status</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">tag</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">tags</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">urn</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">vcpus</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">volume_ids</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">vpc_uuid</span><span class="o">=</span><span class="default_value">None</span></em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_digitalocean.AwaitableGetDropletResult" title="Permalink to this definition">¶</a></dt>
<dd></dd></dl>

<dl class="py class">
<dt id="pulumi_digitalocean.AwaitableGetDropletSnapshotResult">
<em class="property">class </em><code class="sig-prename descclassname">pulumi_digitalocean.</code><code class="sig-name descname">AwaitableGetDropletSnapshotResult</code><span class="sig-paren">(</span><em class="sig-param"><span class="n">created_at</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">droplet_id</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">id</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">min_disk_size</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">most_recent</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">name</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">name_regex</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">region</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">regions</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">size</span><span class="o">=</span><span class="default_value">None</span></em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_digitalocean.AwaitableGetDropletSnapshotResult" title="Permalink to this definition">¶</a></dt>
<dd></dd></dl>

<dl class="py class">
<dt id="pulumi_digitalocean.AwaitableGetDropletsResult">
<em class="property">class </em><code class="sig-prename descclassname">pulumi_digitalocean.</code><code class="sig-name descname">AwaitableGetDropletsResult</code><span class="sig-paren">(</span><em class="sig-param"><span class="n">droplets</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">filters</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">id</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">sorts</span><span class="o">=</span><span class="default_value">None</span></em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_digitalocean.AwaitableGetDropletsResult" title="Permalink to this definition">¶</a></dt>
<dd></dd></dl>

<dl class="py class">
<dt id="pulumi_digitalocean.AwaitableGetFloatingIpResult">
<em class="property">class </em><code class="sig-prename descclassname">pulumi_digitalocean.</code><code class="sig-name descname">AwaitableGetFloatingIpResult</code><span class="sig-paren">(</span><em class="sig-param"><span class="n">droplet_id</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">id</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">ip_address</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">region</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">urn</span><span class="o">=</span><span class="default_value">None</span></em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_digitalocean.AwaitableGetFloatingIpResult" title="Permalink to this definition">¶</a></dt>
<dd></dd></dl>

<dl class="py class">
<dt id="pulumi_digitalocean.AwaitableGetImageResult">
<em class="property">class </em><code class="sig-prename descclassname">pulumi_digitalocean.</code><code class="sig-name descname">AwaitableGetImageResult</code><span class="sig-paren">(</span><em class="sig-param"><span class="n">created</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">distribution</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">error_message</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">id</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">image</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">min_disk_size</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">name</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">private</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">regions</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">size_gigabytes</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">slug</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">source</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">status</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">tags</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">type</span><span class="o">=</span><span class="default_value">None</span></em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_digitalocean.AwaitableGetImageResult" title="Permalink to this definition">¶</a></dt>
<dd></dd></dl>

<dl class="py class">
<dt id="pulumi_digitalocean.AwaitableGetImagesResult">
<em class="property">class </em><code class="sig-prename descclassname">pulumi_digitalocean.</code><code class="sig-name descname">AwaitableGetImagesResult</code><span class="sig-paren">(</span><em class="sig-param"><span class="n">filters</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">id</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">images</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">sorts</span><span class="o">=</span><span class="default_value">None</span></em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_digitalocean.AwaitableGetImagesResult" title="Permalink to this definition">¶</a></dt>
<dd></dd></dl>

<dl class="py class">
<dt id="pulumi_digitalocean.AwaitableGetKubernetesClusterResult">
<em class="property">class </em><code class="sig-prename descclassname">pulumi_digitalocean.</code><code class="sig-name descname">AwaitableGetKubernetesClusterResult</code><span class="sig-paren">(</span><em class="sig-param"><span class="n">cluster_subnet</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">created_at</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">endpoint</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">id</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">ipv4_address</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">kube_configs</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">name</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">node_pools</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">region</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">service_subnet</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">status</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">tags</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">updated_at</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">version</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">vpc_uuid</span><span class="o">=</span><span class="default_value">None</span></em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_digitalocean.AwaitableGetKubernetesClusterResult" title="Permalink to this definition">¶</a></dt>
<dd></dd></dl>

<dl class="py class">
<dt id="pulumi_digitalocean.AwaitableGetKubernetesVersionsResult">
<em class="property">class </em><code class="sig-prename descclassname">pulumi_digitalocean.</code><code class="sig-name descname">AwaitableGetKubernetesVersionsResult</code><span class="sig-paren">(</span><em class="sig-param"><span class="n">id</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">latest_version</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">valid_versions</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">version_prefix</span><span class="o">=</span><span class="default_value">None</span></em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_digitalocean.AwaitableGetKubernetesVersionsResult" title="Permalink to this definition">¶</a></dt>
<dd></dd></dl>

<dl class="py class">
<dt id="pulumi_digitalocean.AwaitableGetLoadBalancerResult">
<em class="property">class </em><code class="sig-prename descclassname">pulumi_digitalocean.</code><code class="sig-name descname">AwaitableGetLoadBalancerResult</code><span class="sig-paren">(</span><em class="sig-param"><span class="n">algorithm</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">droplet_ids</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">droplet_tag</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">enable_backend_keepalive</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">enable_proxy_protocol</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">forwarding_rules</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">healthcheck</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">id</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">ip</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">name</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">redirect_http_to_https</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">region</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">status</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">sticky_sessions</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">urn</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">vpc_uuid</span><span class="o">=</span><span class="default_value">None</span></em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_digitalocean.AwaitableGetLoadBalancerResult" title="Permalink to this definition">¶</a></dt>
<dd></dd></dl>

<dl class="py class">
<dt id="pulumi_digitalocean.AwaitableGetProjectResult">
<em class="property">class </em><code class="sig-prename descclassname">pulumi_digitalocean.</code><code class="sig-name descname">AwaitableGetProjectResult</code><span class="sig-paren">(</span><em class="sig-param"><span class="n">created_at</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">description</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">environment</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">id</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">is_default</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">name</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">owner_id</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">owner_uuid</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">purpose</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">resources</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">updated_at</span><span class="o">=</span><span class="default_value">None</span></em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_digitalocean.AwaitableGetProjectResult" title="Permalink to this definition">¶</a></dt>
<dd></dd></dl>

<dl class="py class">
<dt id="pulumi_digitalocean.AwaitableGetProjectsResult">
<em class="property">class </em><code class="sig-prename descclassname">pulumi_digitalocean.</code><code class="sig-name descname">AwaitableGetProjectsResult</code><span class="sig-paren">(</span><em class="sig-param"><span class="n">filters</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">id</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">projects</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">sorts</span><span class="o">=</span><span class="default_value">None</span></em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_digitalocean.AwaitableGetProjectsResult" title="Permalink to this definition">¶</a></dt>
<dd></dd></dl>

<dl class="py class">
<dt id="pulumi_digitalocean.AwaitableGetRecordResult">
<em class="property">class </em><code class="sig-prename descclassname">pulumi_digitalocean.</code><code class="sig-name descname">AwaitableGetRecordResult</code><span class="sig-paren">(</span><em class="sig-param"><span class="n">data</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">domain</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">flags</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">id</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">name</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">port</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">priority</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">tag</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">ttl</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">type</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">weight</span><span class="o">=</span><span class="default_value">None</span></em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_digitalocean.AwaitableGetRecordResult" title="Permalink to this definition">¶</a></dt>
<dd></dd></dl>

<dl class="py class">
<dt id="pulumi_digitalocean.AwaitableGetRegionResult">
<em class="property">class </em><code class="sig-prename descclassname">pulumi_digitalocean.</code><code class="sig-name descname">AwaitableGetRegionResult</code><span class="sig-paren">(</span><em class="sig-param"><span class="n">available</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">features</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">id</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">name</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">sizes</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">slug</span><span class="o">=</span><span class="default_value">None</span></em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_digitalocean.AwaitableGetRegionResult" title="Permalink to this definition">¶</a></dt>
<dd></dd></dl>

<dl class="py class">
<dt id="pulumi_digitalocean.AwaitableGetRegionsResult">
<em class="property">class </em><code class="sig-prename descclassname">pulumi_digitalocean.</code><code class="sig-name descname">AwaitableGetRegionsResult</code><span class="sig-paren">(</span><em class="sig-param"><span class="n">filters</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">id</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">regions</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">sorts</span><span class="o">=</span><span class="default_value">None</span></em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_digitalocean.AwaitableGetRegionsResult" title="Permalink to this definition">¶</a></dt>
<dd></dd></dl>

<dl class="py class">
<dt id="pulumi_digitalocean.AwaitableGetSizesResult">
<em class="property">class </em><code class="sig-prename descclassname">pulumi_digitalocean.</code><code class="sig-name descname">AwaitableGetSizesResult</code><span class="sig-paren">(</span><em class="sig-param"><span class="n">filters</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">id</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">sizes</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">sorts</span><span class="o">=</span><span class="default_value">None</span></em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_digitalocean.AwaitableGetSizesResult" title="Permalink to this definition">¶</a></dt>
<dd></dd></dl>

<dl class="py class">
<dt id="pulumi_digitalocean.AwaitableGetSpacesBucketObjectResult">
<em class="property">class </em><code class="sig-prename descclassname">pulumi_digitalocean.</code><code class="sig-name descname">AwaitableGetSpacesBucketObjectResult</code><span class="sig-paren">(</span><em class="sig-param"><span class="n">body</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">bucket</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">cache_control</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">content_disposition</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">content_encoding</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">content_language</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">content_length</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">content_type</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">etag</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">expiration</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">expires</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">id</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">key</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">last_modified</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">metadata</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">range</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">region</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">version_id</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">website_redirect_location</span><span class="o">=</span><span class="default_value">None</span></em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_digitalocean.AwaitableGetSpacesBucketObjectResult" title="Permalink to this definition">¶</a></dt>
<dd></dd></dl>

<dl class="py class">
<dt id="pulumi_digitalocean.AwaitableGetSpacesBucketObjectsResult">
<em class="property">class </em><code class="sig-prename descclassname">pulumi_digitalocean.</code><code class="sig-name descname">AwaitableGetSpacesBucketObjectsResult</code><span class="sig-paren">(</span><em class="sig-param"><span class="n">bucket</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">common_prefixes</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">delimiter</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">encoding_type</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">id</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">keys</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">max_keys</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">owners</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">prefix</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">region</span><span class="o">=</span><span class="default_value">None</span></em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_digitalocean.AwaitableGetSpacesBucketObjectsResult" title="Permalink to this definition">¶</a></dt>
<dd></dd></dl>

<dl class="py class">
<dt id="pulumi_digitalocean.AwaitableGetSpacesBucketResult">
<em class="property">class </em><code class="sig-prename descclassname">pulumi_digitalocean.</code><code class="sig-name descname">AwaitableGetSpacesBucketResult</code><span class="sig-paren">(</span><em class="sig-param"><span class="n">bucket_domain_name</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">id</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">name</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">region</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">urn</span><span class="o">=</span><span class="default_value">None</span></em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_digitalocean.AwaitableGetSpacesBucketResult" title="Permalink to this definition">¶</a></dt>
<dd></dd></dl>

<dl class="py class">
<dt id="pulumi_digitalocean.AwaitableGetSpacesBucketsResult">
<em class="property">class </em><code class="sig-prename descclassname">pulumi_digitalocean.</code><code class="sig-name descname">AwaitableGetSpacesBucketsResult</code><span class="sig-paren">(</span><em class="sig-param"><span class="n">buckets</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">filters</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">id</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">sorts</span><span class="o">=</span><span class="default_value">None</span></em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_digitalocean.AwaitableGetSpacesBucketsResult" title="Permalink to this definition">¶</a></dt>
<dd></dd></dl>

<dl class="py class">
<dt id="pulumi_digitalocean.AwaitableGetSshKeyResult">
<em class="property">class </em><code class="sig-prename descclassname">pulumi_digitalocean.</code><code class="sig-name descname">AwaitableGetSshKeyResult</code><span class="sig-paren">(</span><em class="sig-param"><span class="n">fingerprint</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">id</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">name</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">public_key</span><span class="o">=</span><span class="default_value">None</span></em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_digitalocean.AwaitableGetSshKeyResult" title="Permalink to this definition">¶</a></dt>
<dd></dd></dl>

<dl class="py class">
<dt id="pulumi_digitalocean.AwaitableGetTagResult">
<em class="property">class </em><code class="sig-prename descclassname">pulumi_digitalocean.</code><code class="sig-name descname">AwaitableGetTagResult</code><span class="sig-paren">(</span><em class="sig-param"><span class="n">id</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">name</span><span class="o">=</span><span class="default_value">None</span></em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_digitalocean.AwaitableGetTagResult" title="Permalink to this definition">¶</a></dt>
<dd></dd></dl>

<dl class="py class">
<dt id="pulumi_digitalocean.AwaitableGetVolumeResult">
<em class="property">class </em><code class="sig-prename descclassname">pulumi_digitalocean.</code><code class="sig-name descname">AwaitableGetVolumeResult</code><span class="sig-paren">(</span><em class="sig-param"><span class="n">description</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">droplet_ids</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">filesystem_label</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">filesystem_type</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">id</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">name</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">region</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">size</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">tags</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">urn</span><span class="o">=</span><span class="default_value">None</span></em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_digitalocean.AwaitableGetVolumeResult" title="Permalink to this definition">¶</a></dt>
<dd></dd></dl>

<dl class="py class">
<dt id="pulumi_digitalocean.AwaitableGetVolumeSnapshotResult">
<em class="property">class </em><code class="sig-prename descclassname">pulumi_digitalocean.</code><code class="sig-name descname">AwaitableGetVolumeSnapshotResult</code><span class="sig-paren">(</span><em class="sig-param"><span class="n">created_at</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">id</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">min_disk_size</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">most_recent</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">name</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">name_regex</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">region</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">regions</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">size</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">tags</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">volume_id</span><span class="o">=</span><span class="default_value">None</span></em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_digitalocean.AwaitableGetVolumeSnapshotResult" title="Permalink to this definition">¶</a></dt>
<dd></dd></dl>

<dl class="py class">
<dt id="pulumi_digitalocean.AwaitableGetVpcResult">
<em class="property">class </em><code class="sig-prename descclassname">pulumi_digitalocean.</code><code class="sig-name descname">AwaitableGetVpcResult</code><span class="sig-paren">(</span><em class="sig-param"><span class="n">created_at</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">default</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">description</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">id</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">ip_range</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">name</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">region</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">urn</span><span class="o">=</span><span class="default_value">None</span></em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_digitalocean.AwaitableGetVpcResult" title="Permalink to this definition">¶</a></dt>
<dd></dd></dl>

<dl class="py class">
<dt id="pulumi_digitalocean.Cdn">
<em class="property">class </em><code class="sig-prename descclassname">pulumi_digitalocean.</code><code class="sig-name descname">Cdn</code><span class="sig-paren">(</span><em class="sig-param"><span class="n">resource_name</span></em>, <em class="sig-param"><span class="n">opts</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">certificate_id</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">custom_domain</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">origin</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">ttl</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">__props__</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">__name__</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">__opts__</span><span class="o">=</span><span class="default_value">None</span></em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_digitalocean.Cdn" title="Permalink to this definition">¶</a></dt>
<dd><p>Provides a DigitalOcean CDN Endpoint resource for use with Spaces.</p>
<div class="highlight-python notranslate"><div class="highlight"><pre><span></span><span class="kn">import</span> <span class="nn">pulumi</span>
<span class="kn">import</span> <span class="nn">pulumi_digitalocean</span> <span class="k">as</span> <span class="nn">digitalocean</span>

<span class="c1"># Create a new Spaces Bucket</span>
<span class="n">mybucket</span> <span class="o">=</span> <span class="n">digitalocean</span><span class="o">.</span><span class="n">SpacesBucket</span><span class="p">(</span><span class="s2">&quot;mybucket&quot;</span><span class="p">,</span>
    <span class="n">region</span><span class="o">=</span><span class="s2">&quot;sfo2&quot;</span><span class="p">,</span>
    <span class="n">acl</span><span class="o">=</span><span class="s2">&quot;public-read&quot;</span><span class="p">)</span>
<span class="c1"># Add a CDN endpoint to the Spaces Bucket</span>
<span class="n">mycdn</span> <span class="o">=</span> <span class="n">digitalocean</span><span class="o">.</span><span class="n">Cdn</span><span class="p">(</span><span class="s2">&quot;mycdn&quot;</span><span class="p">,</span> <span class="n">origin</span><span class="o">=</span><span class="n">mybucket</span><span class="o">.</span><span class="n">bucket_domain_name</span><span class="p">)</span>
<span class="n">pulumi</span><span class="o">.</span><span class="n">export</span><span class="p">(</span><span class="s2">&quot;fqdn&quot;</span><span class="p">,</span> <span class="n">mycdn</span><span class="o">.</span><span class="n">endpoint</span><span class="p">)</span>
</pre></div>
</div>
<div class="highlight-python notranslate"><div class="highlight"><pre><span></span><span class="kn">import</span> <span class="nn">pulumi</span>
<span class="kn">import</span> <span class="nn">pulumi_digitalocean</span> <span class="k">as</span> <span class="nn">digitalocean</span>

<span class="c1"># Create a new Spaces Bucket</span>
<span class="n">mybucket</span> <span class="o">=</span> <span class="n">digitalocean</span><span class="o">.</span><span class="n">SpacesBucket</span><span class="p">(</span><span class="s2">&quot;mybucket&quot;</span><span class="p">,</span>
    <span class="n">region</span><span class="o">=</span><span class="s2">&quot;sfo2&quot;</span><span class="p">,</span>
    <span class="n">acl</span><span class="o">=</span><span class="s2">&quot;public-read&quot;</span><span class="p">)</span>
<span class="c1"># Create a DigitalOcean managed Let&#39;s Encrypt Certificate</span>
<span class="n">cert</span> <span class="o">=</span> <span class="n">digitalocean</span><span class="o">.</span><span class="n">Certificate</span><span class="p">(</span><span class="s2">&quot;cert&quot;</span><span class="p">,</span>
    <span class="nb">type</span><span class="o">=</span><span class="s2">&quot;lets_encrypt&quot;</span><span class="p">,</span>
    <span class="n">domains</span><span class="o">=</span><span class="p">[</span><span class="s2">&quot;static.example.com&quot;</span><span class="p">])</span>
<span class="c1"># Add a CDN endpoint with a custom sub-domain to the Spaces Bucket</span>
<span class="n">mycdn</span> <span class="o">=</span> <span class="n">digitalocean</span><span class="o">.</span><span class="n">Cdn</span><span class="p">(</span><span class="s2">&quot;mycdn&quot;</span><span class="p">,</span>
    <span class="n">origin</span><span class="o">=</span><span class="n">mybucket</span><span class="o">.</span><span class="n">bucket_domain_name</span><span class="p">,</span>
    <span class="n">custom_domain</span><span class="o">=</span><span class="s2">&quot;static.example.com&quot;</span><span class="p">,</span>
    <span class="n">certificate_id</span><span class="o">=</span><span class="n">cert</span><span class="o">.</span><span class="n">id</span><span class="p">)</span>
</pre></div>
</div>
<dl class="field-list simple">
<dt class="field-odd">Parameters</dt>
<dd class="field-odd"><ul class="simple">
<li><p><strong>resource_name</strong> (<em>str</em>) – The name of the resource.</p></li>
<li><p><strong>opts</strong> (<a class="reference internal" href="../pulumi/#pulumi.ResourceOptions" title="pulumi.ResourceOptions"><em>pulumi.ResourceOptions</em></a>) – Options for the resource.</p></li>
<li><p><strong>certificate_id</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – The ID of a DigitalOcean managed TLS certificate used for SSL when a custom subdomain is provided.</p></li>
<li><p><strong>custom_domain</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – The fully qualified domain name (FQDN) of the custom subdomain used with the CDN Endpoint.</p></li>
<li><p><strong>origin</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – The fully qualified domain name, (FQDN) for a Space.</p></li>
<li><p><strong>ttl</strong> (<em>pulumi.Input</em><em>[</em><em>float</em><em>]</em>) – The time to live for the CDN Endpoint, in seconds. Default is 3600 seconds.</p></li>
</ul>
</dd>
</dl>
<dl class="py attribute">
<dt id="pulumi_digitalocean.Cdn.certificate_id">
<code class="sig-name descname">certificate_id</code><em class="property">: pulumi.Output[str]</em><em class="property"> = None</em><a class="headerlink" href="#pulumi_digitalocean.Cdn.certificate_id" title="Permalink to this definition">¶</a></dt>
<dd><p>The ID of a DigitalOcean managed TLS certificate used for SSL when a custom subdomain is provided.</p>
</dd></dl>

<dl class="py attribute">
<dt id="pulumi_digitalocean.Cdn.created_at">
<code class="sig-name descname">created_at</code><em class="property">: pulumi.Output[str]</em><em class="property"> = None</em><a class="headerlink" href="#pulumi_digitalocean.Cdn.created_at" title="Permalink to this definition">¶</a></dt>
<dd><p>The date and time when the CDN Endpoint was created.</p>
</dd></dl>

<dl class="py attribute">
<dt id="pulumi_digitalocean.Cdn.custom_domain">
<code class="sig-name descname">custom_domain</code><em class="property">: pulumi.Output[str]</em><em class="property"> = None</em><a class="headerlink" href="#pulumi_digitalocean.Cdn.custom_domain" title="Permalink to this definition">¶</a></dt>
<dd><p>The fully qualified domain name (FQDN) of the custom subdomain used with the CDN Endpoint.</p>
</dd></dl>

<dl class="py attribute">
<dt id="pulumi_digitalocean.Cdn.endpoint">
<code class="sig-name descname">endpoint</code><em class="property">: pulumi.Output[str]</em><em class="property"> = None</em><a class="headerlink" href="#pulumi_digitalocean.Cdn.endpoint" title="Permalink to this definition">¶</a></dt>
<dd><p>The fully qualified domain name (FQDN) from which the CDN-backed content is served.</p>
</dd></dl>

<dl class="py attribute">
<dt id="pulumi_digitalocean.Cdn.origin">
<code class="sig-name descname">origin</code><em class="property">: pulumi.Output[str]</em><em class="property"> = None</em><a class="headerlink" href="#pulumi_digitalocean.Cdn.origin" title="Permalink to this definition">¶</a></dt>
<dd><p>The fully qualified domain name, (FQDN) for a Space.</p>
</dd></dl>

<dl class="py attribute">
<dt id="pulumi_digitalocean.Cdn.ttl">
<code class="sig-name descname">ttl</code><em class="property">: pulumi.Output[float]</em><em class="property"> = None</em><a class="headerlink" href="#pulumi_digitalocean.Cdn.ttl" title="Permalink to this definition">¶</a></dt>
<dd><p>The time to live for the CDN Endpoint, in seconds. Default is 3600 seconds.</p>
</dd></dl>

<dl class="py method">
<dt id="pulumi_digitalocean.Cdn.get">
<em class="property">static </em><code class="sig-name descname">get</code><span class="sig-paren">(</span><em class="sig-param"><span class="n">resource_name</span></em>, <em class="sig-param"><span class="n">id</span></em>, <em class="sig-param"><span class="n">opts</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">certificate_id</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">created_at</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">custom_domain</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">endpoint</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">origin</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">ttl</span><span class="o">=</span><span class="default_value">None</span></em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_digitalocean.Cdn.get" title="Permalink to this definition">¶</a></dt>
<dd><p>Get an existing Cdn resource’s state with the given name, id, and optional extra
properties used to qualify the lookup.</p>
<dl class="field-list simple">
<dt class="field-odd">Parameters</dt>
<dd class="field-odd"><ul class="simple">
<li><p><strong>resource_name</strong> (<em>str</em>) – The unique name of the resulting resource.</p></li>
<li><p><strong>id</strong> (<em>str</em>) – The unique provider ID of the resource to lookup.</p></li>
<li><p><strong>opts</strong> (<a class="reference internal" href="../pulumi/#pulumi.ResourceOptions" title="pulumi.ResourceOptions"><em>pulumi.ResourceOptions</em></a>) – Options for the resource.</p></li>
<li><p><strong>certificate_id</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – The ID of a DigitalOcean managed TLS certificate used for SSL when a custom subdomain is provided.</p></li>
<li><p><strong>created_at</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – The date and time when the CDN Endpoint was created.</p></li>
<li><p><strong>custom_domain</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – The fully qualified domain name (FQDN) of the custom subdomain used with the CDN Endpoint.</p></li>
<li><p><strong>endpoint</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – The fully qualified domain name (FQDN) from which the CDN-backed content is served.</p></li>
<li><p><strong>origin</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – The fully qualified domain name, (FQDN) for a Space.</p></li>
<li><p><strong>ttl</strong> (<em>pulumi.Input</em><em>[</em><em>float</em><em>]</em>) – The time to live for the CDN Endpoint, in seconds. Default is 3600 seconds.</p></li>
</ul>
</dd>
</dl>
</dd></dl>

<dl class="py method">
<dt id="pulumi_digitalocean.Cdn.translate_output_property">
<code class="sig-name descname">translate_output_property</code><span class="sig-paren">(</span><em class="sig-param"><span class="n">prop</span></em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_digitalocean.Cdn.translate_output_property" title="Permalink to this definition">¶</a></dt>
<dd><p>Provides subclasses of Resource an opportunity to translate names of output properties
into a format of their choosing before writing those properties to the resource object.</p>
<dl class="field-list simple">
<dt class="field-odd">Parameters</dt>
<dd class="field-odd"><p><strong>prop</strong> (<em>str</em>) – A property name.</p>
</dd>
<dt class="field-even">Returns</dt>
<dd class="field-even"><p>A potentially transformed property name.</p>
</dd>
<dt class="field-odd">Return type</dt>
<dd class="field-odd"><p>str</p>
</dd>
</dl>
</dd></dl>

<dl class="py method">
<dt id="pulumi_digitalocean.Cdn.translate_input_property">
<code class="sig-name descname">translate_input_property</code><span class="sig-paren">(</span><em class="sig-param"><span class="n">prop</span></em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_digitalocean.Cdn.translate_input_property" title="Permalink to this definition">¶</a></dt>
<dd><p>Provides subclasses of Resource an opportunity to translate names of input properties into
a format of their choosing before sending those properties to the Pulumi engine.</p>
<dl class="field-list simple">
<dt class="field-odd">Parameters</dt>
<dd class="field-odd"><p><strong>prop</strong> (<em>str</em>) – A property name.</p>
</dd>
<dt class="field-even">Returns</dt>
<dd class="field-even"><p>A potentially transformed property name.</p>
</dd>
<dt class="field-odd">Return type</dt>
<dd class="field-odd"><p>str</p>
</dd>
</dl>
</dd></dl>

</dd></dl>

<dl class="py class">
<dt id="pulumi_digitalocean.Certificate">
<em class="property">class </em><code class="sig-prename descclassname">pulumi_digitalocean.</code><code class="sig-name descname">Certificate</code><span class="sig-paren">(</span><em class="sig-param"><span class="n">resource_name</span></em>, <em class="sig-param"><span class="n">opts</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">certificate_chain</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">domains</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">leaf_certificate</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">name</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">private_key</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">type</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">__props__</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">__name__</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">__opts__</span><span class="o">=</span><span class="default_value">None</span></em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_digitalocean.Certificate" title="Permalink to this definition">¶</a></dt>
<dd><p>Create a Certificate resource with the given unique name, props, and options.
:param str resource_name: The name of the resource.
:param pulumi.ResourceOptions opts: Options for the resource.
:param pulumi.Input[str] certificate_chain: The full PEM-formatted trust chain</p>
<blockquote>
<div><p>between the certificate authority’s certificate and your domain’s TLS
certificate. Only valid when type is <code class="docutils literal notranslate"><span class="pre">custom</span></code>.</p>
</div></blockquote>
<dl class="field-list simple">
<dt class="field-odd">Parameters</dt>
<dd class="field-odd"><ul class="simple">
<li><p><strong>domains</strong> (<em>pulumi.Input</em><em>[</em><em>list</em><em>]</em>) – List of fully qualified domain names (FQDNs) for
which the certificate will be issued. The domains must be managed using
DigitalOcean’s DNS. Only valid when type is <code class="docutils literal notranslate"><span class="pre">lets_encrypt</span></code>.</p></li>
<li><p><strong>leaf_certificate</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – The contents of a PEM-formatted public
TLS certificate. Only valid when type is <code class="docutils literal notranslate"><span class="pre">custom</span></code>.</p></li>
<li><p><strong>name</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – The name of the certificate for identification.</p></li>
<li><p><strong>private_key</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – The contents of a PEM-formatted private-key
corresponding to the SSL certificate. Only valid when type is <code class="docutils literal notranslate"><span class="pre">custom</span></code>.</p></li>
<li><p><strong>type</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – The type of certificate to provision. Can be either
<code class="docutils literal notranslate"><span class="pre">custom</span></code> or <code class="docutils literal notranslate"><span class="pre">lets_encrypt</span></code>. Defaults to <code class="docutils literal notranslate"><span class="pre">custom</span></code>.</p></li>
</ul>
</dd>
</dl>
<dl class="py attribute">
<dt id="pulumi_digitalocean.Certificate.certificate_chain">
<code class="sig-name descname">certificate_chain</code><em class="property">: pulumi.Output[str]</em><em class="property"> = None</em><a class="headerlink" href="#pulumi_digitalocean.Certificate.certificate_chain" title="Permalink to this definition">¶</a></dt>
<dd><p>The full PEM-formatted trust chain
between the certificate authority’s certificate and your domain’s TLS
certificate. Only valid when type is <code class="docutils literal notranslate"><span class="pre">custom</span></code>.</p>
</dd></dl>

<dl class="py attribute">
<dt id="pulumi_digitalocean.Certificate.domains">
<code class="sig-name descname">domains</code><em class="property">: pulumi.Output[list]</em><em class="property"> = None</em><a class="headerlink" href="#pulumi_digitalocean.Certificate.domains" title="Permalink to this definition">¶</a></dt>
<dd><p>List of fully qualified domain names (FQDNs) for
which the certificate will be issued. The domains must be managed using
DigitalOcean’s DNS. Only valid when type is <code class="docutils literal notranslate"><span class="pre">lets_encrypt</span></code>.</p>
</dd></dl>

<dl class="py attribute">
<dt id="pulumi_digitalocean.Certificate.leaf_certificate">
<code class="sig-name descname">leaf_certificate</code><em class="property">: pulumi.Output[str]</em><em class="property"> = None</em><a class="headerlink" href="#pulumi_digitalocean.Certificate.leaf_certificate" title="Permalink to this definition">¶</a></dt>
<dd><p>The contents of a PEM-formatted public
TLS certificate. Only valid when type is <code class="docutils literal notranslate"><span class="pre">custom</span></code>.</p>
</dd></dl>

<dl class="py attribute">
<dt id="pulumi_digitalocean.Certificate.name">
<code class="sig-name descname">name</code><em class="property">: pulumi.Output[str]</em><em class="property"> = None</em><a class="headerlink" href="#pulumi_digitalocean.Certificate.name" title="Permalink to this definition">¶</a></dt>
<dd><p>The name of the certificate for identification.</p>
</dd></dl>

<dl class="py attribute">
<dt id="pulumi_digitalocean.Certificate.not_after">
<code class="sig-name descname">not_after</code><em class="property">: pulumi.Output[str]</em><em class="property"> = None</em><a class="headerlink" href="#pulumi_digitalocean.Certificate.not_after" title="Permalink to this definition">¶</a></dt>
<dd><p>The expiration date of the certificate</p>
</dd></dl>

<dl class="py attribute">
<dt id="pulumi_digitalocean.Certificate.private_key">
<code class="sig-name descname">private_key</code><em class="property">: pulumi.Output[str]</em><em class="property"> = None</em><a class="headerlink" href="#pulumi_digitalocean.Certificate.private_key" title="Permalink to this definition">¶</a></dt>
<dd><p>The contents of a PEM-formatted private-key
corresponding to the SSL certificate. Only valid when type is <code class="docutils literal notranslate"><span class="pre">custom</span></code>.</p>
</dd></dl>

<dl class="py attribute">
<dt id="pulumi_digitalocean.Certificate.sha1_fingerprint">
<code class="sig-name descname">sha1_fingerprint</code><em class="property">: pulumi.Output[str]</em><em class="property"> = None</em><a class="headerlink" href="#pulumi_digitalocean.Certificate.sha1_fingerprint" title="Permalink to this definition">¶</a></dt>
<dd><p>The SHA-1 fingerprint of the certificate</p>
</dd></dl>

<dl class="py attribute">
<dt id="pulumi_digitalocean.Certificate.type">
<code class="sig-name descname">type</code><em class="property">: pulumi.Output[str]</em><em class="property"> = None</em><a class="headerlink" href="#pulumi_digitalocean.Certificate.type" title="Permalink to this definition">¶</a></dt>
<dd><p>The type of certificate to provision. Can be either
<code class="docutils literal notranslate"><span class="pre">custom</span></code> or <code class="docutils literal notranslate"><span class="pre">lets_encrypt</span></code>. Defaults to <code class="docutils literal notranslate"><span class="pre">custom</span></code>.</p>
</dd></dl>

<dl class="py method">
<dt id="pulumi_digitalocean.Certificate.get">
<em class="property">static </em><code class="sig-name descname">get</code><span class="sig-paren">(</span><em class="sig-param"><span class="n">resource_name</span></em>, <em class="sig-param"><span class="n">id</span></em>, <em class="sig-param"><span class="n">opts</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">certificate_chain</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">domains</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">leaf_certificate</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">name</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">not_after</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">private_key</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">sha1_fingerprint</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">state</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">type</span><span class="o">=</span><span class="default_value">None</span></em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_digitalocean.Certificate.get" title="Permalink to this definition">¶</a></dt>
<dd><p>Get an existing Certificate resource’s state with the given name, id, and optional extra
properties used to qualify the lookup.</p>
<dl class="field-list simple">
<dt class="field-odd">Parameters</dt>
<dd class="field-odd"><ul class="simple">
<li><p><strong>resource_name</strong> (<em>str</em>) – The unique name of the resulting resource.</p></li>
<li><p><strong>id</strong> (<em>str</em>) – The unique provider ID of the resource to lookup.</p></li>
<li><p><strong>opts</strong> (<a class="reference internal" href="../pulumi/#pulumi.ResourceOptions" title="pulumi.ResourceOptions"><em>pulumi.ResourceOptions</em></a>) – Options for the resource.</p></li>
<li><p><strong>certificate_chain</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – The full PEM-formatted trust chain
between the certificate authority’s certificate and your domain’s TLS
certificate. Only valid when type is <code class="docutils literal notranslate"><span class="pre">custom</span></code>.</p></li>
<li><p><strong>domains</strong> (<em>pulumi.Input</em><em>[</em><em>list</em><em>]</em>) – List of fully qualified domain names (FQDNs) for
which the certificate will be issued. The domains must be managed using
DigitalOcean’s DNS. Only valid when type is <code class="docutils literal notranslate"><span class="pre">lets_encrypt</span></code>.</p></li>
<li><p><strong>leaf_certificate</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – The contents of a PEM-formatted public
TLS certificate. Only valid when type is <code class="docutils literal notranslate"><span class="pre">custom</span></code>.</p></li>
<li><p><strong>name</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – The name of the certificate for identification.</p></li>
<li><p><strong>not_after</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – The expiration date of the certificate</p></li>
<li><p><strong>private_key</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – The contents of a PEM-formatted private-key
corresponding to the SSL certificate. Only valid when type is <code class="docutils literal notranslate"><span class="pre">custom</span></code>.</p></li>
<li><p><strong>sha1_fingerprint</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – The SHA-1 fingerprint of the certificate</p></li>
<li><p><strong>type</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – The type of certificate to provision. Can be either
<code class="docutils literal notranslate"><span class="pre">custom</span></code> or <code class="docutils literal notranslate"><span class="pre">lets_encrypt</span></code>. Defaults to <code class="docutils literal notranslate"><span class="pre">custom</span></code>.</p></li>
</ul>
</dd>
</dl>
</dd></dl>

<dl class="py method">
<dt id="pulumi_digitalocean.Certificate.translate_output_property">
<code class="sig-name descname">translate_output_property</code><span class="sig-paren">(</span><em class="sig-param"><span class="n">prop</span></em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_digitalocean.Certificate.translate_output_property" title="Permalink to this definition">¶</a></dt>
<dd><p>Provides subclasses of Resource an opportunity to translate names of output properties
into a format of their choosing before writing those properties to the resource object.</p>
<dl class="field-list simple">
<dt class="field-odd">Parameters</dt>
<dd class="field-odd"><p><strong>prop</strong> (<em>str</em>) – A property name.</p>
</dd>
<dt class="field-even">Returns</dt>
<dd class="field-even"><p>A potentially transformed property name.</p>
</dd>
<dt class="field-odd">Return type</dt>
<dd class="field-odd"><p>str</p>
</dd>
</dl>
</dd></dl>

<dl class="py method">
<dt id="pulumi_digitalocean.Certificate.translate_input_property">
<code class="sig-name descname">translate_input_property</code><span class="sig-paren">(</span><em class="sig-param"><span class="n">prop</span></em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_digitalocean.Certificate.translate_input_property" title="Permalink to this definition">¶</a></dt>
<dd><p>Provides subclasses of Resource an opportunity to translate names of input properties into
a format of their choosing before sending those properties to the Pulumi engine.</p>
<dl class="field-list simple">
<dt class="field-odd">Parameters</dt>
<dd class="field-odd"><p><strong>prop</strong> (<em>str</em>) – A property name.</p>
</dd>
<dt class="field-even">Returns</dt>
<dd class="field-even"><p>A potentially transformed property name.</p>
</dd>
<dt class="field-odd">Return type</dt>
<dd class="field-odd"><p>str</p>
</dd>
</dl>
</dd></dl>

</dd></dl>

<dl class="py class">
<dt id="pulumi_digitalocean.DatabaseCluster">
<em class="property">class </em><code class="sig-prename descclassname">pulumi_digitalocean.</code><code class="sig-name descname">DatabaseCluster</code><span class="sig-paren">(</span><em class="sig-param"><span class="n">resource_name</span></em>, <em class="sig-param"><span class="n">opts</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">engine</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">eviction_policy</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">maintenance_windows</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">name</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">node_count</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">private_network_uuid</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">region</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">size</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">sql_mode</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">tags</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">version</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">__props__</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">__name__</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">__opts__</span><span class="o">=</span><span class="default_value">None</span></em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_digitalocean.DatabaseCluster" title="Permalink to this definition">¶</a></dt>
<dd><p>Provides a DigitalOcean database cluster resource.</p>
<div class="highlight-python notranslate"><div class="highlight"><pre><span></span><span class="kn">import</span> <span class="nn">pulumi</span>
<span class="kn">import</span> <span class="nn">pulumi_digitalocean</span> <span class="k">as</span> <span class="nn">digitalocean</span>

<span class="n">postgres_example</span> <span class="o">=</span> <span class="n">digitalocean</span><span class="o">.</span><span class="n">DatabaseCluster</span><span class="p">(</span><span class="s2">&quot;postgres-example&quot;</span><span class="p">,</span>
    <span class="n">engine</span><span class="o">=</span><span class="s2">&quot;pg&quot;</span><span class="p">,</span>
    <span class="n">node_count</span><span class="o">=</span><span class="mi">1</span><span class="p">,</span>
    <span class="n">region</span><span class="o">=</span><span class="s2">&quot;nyc1&quot;</span><span class="p">,</span>
    <span class="n">size</span><span class="o">=</span><span class="s2">&quot;db-s-1vcpu-1gb&quot;</span><span class="p">,</span>
    <span class="n">version</span><span class="o">=</span><span class="s2">&quot;11&quot;</span><span class="p">)</span>
</pre></div>
</div>
<div class="highlight-python notranslate"><div class="highlight"><pre><span></span><span class="kn">import</span> <span class="nn">pulumi</span>
<span class="kn">import</span> <span class="nn">pulumi_digitalocean</span> <span class="k">as</span> <span class="nn">digitalocean</span>

<span class="n">mysql_example</span> <span class="o">=</span> <span class="n">digitalocean</span><span class="o">.</span><span class="n">DatabaseCluster</span><span class="p">(</span><span class="s2">&quot;mysql-example&quot;</span><span class="p">,</span>
    <span class="n">engine</span><span class="o">=</span><span class="s2">&quot;mysql&quot;</span><span class="p">,</span>
    <span class="n">node_count</span><span class="o">=</span><span class="mi">1</span><span class="p">,</span>
    <span class="n">region</span><span class="o">=</span><span class="s2">&quot;nyc1&quot;</span><span class="p">,</span>
    <span class="n">size</span><span class="o">=</span><span class="s2">&quot;db-s-1vcpu-1gb&quot;</span><span class="p">,</span>
    <span class="n">version</span><span class="o">=</span><span class="s2">&quot;8&quot;</span><span class="p">)</span>
</pre></div>
</div>
<div class="highlight-python notranslate"><div class="highlight"><pre><span></span><span class="kn">import</span> <span class="nn">pulumi</span>
<span class="kn">import</span> <span class="nn">pulumi_digitalocean</span> <span class="k">as</span> <span class="nn">digitalocean</span>

<span class="n">redis_example</span> <span class="o">=</span> <span class="n">digitalocean</span><span class="o">.</span><span class="n">DatabaseCluster</span><span class="p">(</span><span class="s2">&quot;redis-example&quot;</span><span class="p">,</span>
    <span class="n">engine</span><span class="o">=</span><span class="s2">&quot;redis&quot;</span><span class="p">,</span>
    <span class="n">node_count</span><span class="o">=</span><span class="mi">1</span><span class="p">,</span>
    <span class="n">region</span><span class="o">=</span><span class="s2">&quot;nyc1&quot;</span><span class="p">,</span>
    <span class="n">size</span><span class="o">=</span><span class="s2">&quot;db-s-1vcpu-1gb&quot;</span><span class="p">,</span>
    <span class="n">version</span><span class="o">=</span><span class="s2">&quot;5&quot;</span><span class="p">)</span>
</pre></div>
</div>
<dl class="field-list simple">
<dt class="field-odd">Parameters</dt>
<dd class="field-odd"><ul class="simple">
<li><p><strong>resource_name</strong> (<em>str</em>) – The name of the resource.</p></li>
<li><p><strong>opts</strong> (<a class="reference internal" href="../pulumi/#pulumi.ResourceOptions" title="pulumi.ResourceOptions"><em>pulumi.ResourceOptions</em></a>) – Options for the resource.</p></li>
<li><p><strong>engine</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – Database engine used by the cluster (ex. <code class="docutils literal notranslate"><span class="pre">pg</span></code> for PostreSQL, <code class="docutils literal notranslate"><span class="pre">mysql</span></code> for MySQL, or <code class="docutils literal notranslate"><span class="pre">redis</span></code> for Redis).</p></li>
<li><p><strong>eviction_policy</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – A string specifying the eviction policy for a Redis cluster. Valid values are: <code class="docutils literal notranslate"><span class="pre">noeviction</span></code>, <code class="docutils literal notranslate"><span class="pre">allkeys_lru</span></code>, <code class="docutils literal notranslate"><span class="pre">allkeys_random</span></code>, <code class="docutils literal notranslate"><span class="pre">volatile_lru</span></code>, <code class="docutils literal notranslate"><span class="pre">volatile_random</span></code>, or <code class="docutils literal notranslate"><span class="pre">volatile_ttl</span></code>.</p></li>
<li><p><strong>maintenance_windows</strong> (<em>pulumi.Input</em><em>[</em><em>list</em><em>]</em>) – Defines when the automatic maintenance should be performed for the database cluster.</p></li>
<li><p><strong>name</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – The name of the database cluster.</p></li>
<li><p><strong>node_count</strong> (<em>pulumi.Input</em><em>[</em><em>float</em><em>]</em>) – Number of nodes that will be included in the cluster.</p></li>
<li><p><strong>private_network_uuid</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – The ID of the VPC where the database cluster will be located.</p></li>
<li><p><strong>region</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – DigitalOcean region where the cluster will reside.</p></li>
<li><p><strong>size</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – Database Droplet size associated with the cluster (ex. <code class="docutils literal notranslate"><span class="pre">db-s-1vcpu-1gb</span></code>).</p></li>
<li><p><strong>sql_mode</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – A comma separated string specifying the  SQL modes for a MySQL cluster.</p></li>
<li><p><strong>tags</strong> (<em>pulumi.Input</em><em>[</em><em>list</em><em>]</em>) – A list of tag names to be applied to the database cluster.</p></li>
<li><p><strong>version</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – Engine version used by the cluster (ex. <code class="docutils literal notranslate"><span class="pre">11</span></code> for PostgreSQL 11).</p></li>
</ul>
</dd>
</dl>
<p>The <strong>maintenance_windows</strong> object supports the following:</p>
<ul class="simple">
<li><p><code class="docutils literal notranslate"><span class="pre">day</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[str]</span></code>) - The day of the week on which to apply maintenance updates.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">hour</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[str]</span></code>) - The hour in UTC at which maintenance updates will be applied in 24 hour format.</p></li>
</ul>
<dl class="py attribute">
<dt id="pulumi_digitalocean.DatabaseCluster.database">
<code class="sig-name descname">database</code><em class="property">: pulumi.Output[str]</em><em class="property"> = None</em><a class="headerlink" href="#pulumi_digitalocean.DatabaseCluster.database" title="Permalink to this definition">¶</a></dt>
<dd><p>Name of the cluster’s default database.</p>
</dd></dl>

<dl class="py attribute">
<dt id="pulumi_digitalocean.DatabaseCluster.engine">
<code class="sig-name descname">engine</code><em class="property">: pulumi.Output[str]</em><em class="property"> = None</em><a class="headerlink" href="#pulumi_digitalocean.DatabaseCluster.engine" title="Permalink to this definition">¶</a></dt>
<dd><p>Database engine used by the cluster (ex. <code class="docutils literal notranslate"><span class="pre">pg</span></code> for PostreSQL, <code class="docutils literal notranslate"><span class="pre">mysql</span></code> for MySQL, or <code class="docutils literal notranslate"><span class="pre">redis</span></code> for Redis).</p>
</dd></dl>

<dl class="py attribute">
<dt id="pulumi_digitalocean.DatabaseCluster.eviction_policy">
<code class="sig-name descname">eviction_policy</code><em class="property">: pulumi.Output[str]</em><em class="property"> = None</em><a class="headerlink" href="#pulumi_digitalocean.DatabaseCluster.eviction_policy" title="Permalink to this definition">¶</a></dt>
<dd><p>A string specifying the eviction policy for a Redis cluster. Valid values are: <code class="docutils literal notranslate"><span class="pre">noeviction</span></code>, <code class="docutils literal notranslate"><span class="pre">allkeys_lru</span></code>, <code class="docutils literal notranslate"><span class="pre">allkeys_random</span></code>, <code class="docutils literal notranslate"><span class="pre">volatile_lru</span></code>, <code class="docutils literal notranslate"><span class="pre">volatile_random</span></code>, or <code class="docutils literal notranslate"><span class="pre">volatile_ttl</span></code>.</p>
</dd></dl>

<dl class="py attribute">
<dt id="pulumi_digitalocean.DatabaseCluster.host">
<code class="sig-name descname">host</code><em class="property">: pulumi.Output[str]</em><em class="property"> = None</em><a class="headerlink" href="#pulumi_digitalocean.DatabaseCluster.host" title="Permalink to this definition">¶</a></dt>
<dd><p>Database cluster’s hostname.</p>
</dd></dl>

<dl class="py attribute">
<dt id="pulumi_digitalocean.DatabaseCluster.maintenance_windows">
<code class="sig-name descname">maintenance_windows</code><em class="property">: pulumi.Output[list]</em><em class="property"> = None</em><a class="headerlink" href="#pulumi_digitalocean.DatabaseCluster.maintenance_windows" title="Permalink to this definition">¶</a></dt>
<dd><p>Defines when the automatic maintenance should be performed for the database cluster.</p>
<ul class="simple">
<li><p><code class="docutils literal notranslate"><span class="pre">day</span></code> (<code class="docutils literal notranslate"><span class="pre">str</span></code>) - The day of the week on which to apply maintenance updates.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">hour</span></code> (<code class="docutils literal notranslate"><span class="pre">str</span></code>) - The hour in UTC at which maintenance updates will be applied in 24 hour format.</p></li>
</ul>
</dd></dl>

<dl class="py attribute">
<dt id="pulumi_digitalocean.DatabaseCluster.name">
<code class="sig-name descname">name</code><em class="property">: pulumi.Output[str]</em><em class="property"> = None</em><a class="headerlink" href="#pulumi_digitalocean.DatabaseCluster.name" title="Permalink to this definition">¶</a></dt>
<dd><p>The name of the database cluster.</p>
</dd></dl>

<dl class="py attribute">
<dt id="pulumi_digitalocean.DatabaseCluster.node_count">
<code class="sig-name descname">node_count</code><em class="property">: pulumi.Output[float]</em><em class="property"> = None</em><a class="headerlink" href="#pulumi_digitalocean.DatabaseCluster.node_count" title="Permalink to this definition">¶</a></dt>
<dd><p>Number of nodes that will be included in the cluster.</p>
</dd></dl>

<dl class="py attribute">
<dt id="pulumi_digitalocean.DatabaseCluster.password">
<code class="sig-name descname">password</code><em class="property">: pulumi.Output[str]</em><em class="property"> = None</em><a class="headerlink" href="#pulumi_digitalocean.DatabaseCluster.password" title="Permalink to this definition">¶</a></dt>
<dd><p>Password for the cluster’s default user.</p>
</dd></dl>

<dl class="py attribute">
<dt id="pulumi_digitalocean.DatabaseCluster.port">
<code class="sig-name descname">port</code><em class="property">: pulumi.Output[float]</em><em class="property"> = None</em><a class="headerlink" href="#pulumi_digitalocean.DatabaseCluster.port" title="Permalink to this definition">¶</a></dt>
<dd><p>Network port that the database cluster is listening on.</p>
</dd></dl>

<dl class="py attribute">
<dt id="pulumi_digitalocean.DatabaseCluster.private_host">
<code class="sig-name descname">private_host</code><em class="property">: pulumi.Output[str]</em><em class="property"> = None</em><a class="headerlink" href="#pulumi_digitalocean.DatabaseCluster.private_host" title="Permalink to this definition">¶</a></dt>
<dd><p>Same as <code class="docutils literal notranslate"><span class="pre">host</span></code>, but only accessible from resources within the account and in the same region.</p>
</dd></dl>

<dl class="py attribute">
<dt id="pulumi_digitalocean.DatabaseCluster.private_network_uuid">
<code class="sig-name descname">private_network_uuid</code><em class="property">: pulumi.Output[str]</em><em class="property"> = None</em><a class="headerlink" href="#pulumi_digitalocean.DatabaseCluster.private_network_uuid" title="Permalink to this definition">¶</a></dt>
<dd><p>The ID of the VPC where the database cluster will be located.</p>
</dd></dl>

<dl class="py attribute">
<dt id="pulumi_digitalocean.DatabaseCluster.private_uri">
<code class="sig-name descname">private_uri</code><em class="property">: pulumi.Output[str]</em><em class="property"> = None</em><a class="headerlink" href="#pulumi_digitalocean.DatabaseCluster.private_uri" title="Permalink to this definition">¶</a></dt>
<dd><p>Same as <code class="docutils literal notranslate"><span class="pre">uri</span></code>, but only accessible from resources within the account and in the same region.</p>
</dd></dl>

<dl class="py attribute">
<dt id="pulumi_digitalocean.DatabaseCluster.region">
<code class="sig-name descname">region</code><em class="property">: pulumi.Output[str]</em><em class="property"> = None</em><a class="headerlink" href="#pulumi_digitalocean.DatabaseCluster.region" title="Permalink to this definition">¶</a></dt>
<dd><p>DigitalOcean region where the cluster will reside.</p>
</dd></dl>

<dl class="py attribute">
<dt id="pulumi_digitalocean.DatabaseCluster.size">
<code class="sig-name descname">size</code><em class="property">: pulumi.Output[str]</em><em class="property"> = None</em><a class="headerlink" href="#pulumi_digitalocean.DatabaseCluster.size" title="Permalink to this definition">¶</a></dt>
<dd><p>Database Droplet size associated with the cluster (ex. <code class="docutils literal notranslate"><span class="pre">db-s-1vcpu-1gb</span></code>).</p>
</dd></dl>

<dl class="py attribute">
<dt id="pulumi_digitalocean.DatabaseCluster.sql_mode">
<code class="sig-name descname">sql_mode</code><em class="property">: pulumi.Output[str]</em><em class="property"> = None</em><a class="headerlink" href="#pulumi_digitalocean.DatabaseCluster.sql_mode" title="Permalink to this definition">¶</a></dt>
<dd><p>A comma separated string specifying the  SQL modes for a MySQL cluster.</p>
</dd></dl>

<dl class="py attribute">
<dt id="pulumi_digitalocean.DatabaseCluster.tags">
<code class="sig-name descname">tags</code><em class="property">: pulumi.Output[list]</em><em class="property"> = None</em><a class="headerlink" href="#pulumi_digitalocean.DatabaseCluster.tags" title="Permalink to this definition">¶</a></dt>
<dd><p>A list of tag names to be applied to the database cluster.</p>
</dd></dl>

<dl class="py attribute">
<dt id="pulumi_digitalocean.DatabaseCluster.uri">
<code class="sig-name descname">uri</code><em class="property">: pulumi.Output[str]</em><em class="property"> = None</em><a class="headerlink" href="#pulumi_digitalocean.DatabaseCluster.uri" title="Permalink to this definition">¶</a></dt>
<dd><p>The full URI for connecting to the database cluster.</p>
</dd></dl>

<dl class="py attribute">
<dt id="pulumi_digitalocean.DatabaseCluster.urn">
<code class="sig-name descname">urn</code><em class="property">: pulumi.Output[str]</em><em class="property"> = None</em><a class="headerlink" href="#pulumi_digitalocean.DatabaseCluster.urn" title="Permalink to this definition">¶</a></dt>
<dd><p>The uniform resource name of the database cluster.</p>
</dd></dl>

<dl class="py attribute">
<dt id="pulumi_digitalocean.DatabaseCluster.user">
<code class="sig-name descname">user</code><em class="property">: pulumi.Output[str]</em><em class="property"> = None</em><a class="headerlink" href="#pulumi_digitalocean.DatabaseCluster.user" title="Permalink to this definition">¶</a></dt>
<dd><p>Username for the cluster’s default user.</p>
</dd></dl>

<dl class="py attribute">
<dt id="pulumi_digitalocean.DatabaseCluster.version">
<code class="sig-name descname">version</code><em class="property">: pulumi.Output[str]</em><em class="property"> = None</em><a class="headerlink" href="#pulumi_digitalocean.DatabaseCluster.version" title="Permalink to this definition">¶</a></dt>
<dd><p>Engine version used by the cluster (ex. <code class="docutils literal notranslate"><span class="pre">11</span></code> for PostgreSQL 11).</p>
</dd></dl>

<dl class="py method">
<dt id="pulumi_digitalocean.DatabaseCluster.get">
<em class="property">static </em><code class="sig-name descname">get</code><span class="sig-paren">(</span><em class="sig-param"><span class="n">resource_name</span></em>, <em class="sig-param"><span class="n">id</span></em>, <em class="sig-param"><span class="n">opts</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">database</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">engine</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">eviction_policy</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">host</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">maintenance_windows</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">name</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">node_count</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">password</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">port</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">private_host</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">private_network_uuid</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">private_uri</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">region</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">size</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">sql_mode</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">tags</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">uri</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">urn</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">user</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">version</span><span class="o">=</span><span class="default_value">None</span></em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_digitalocean.DatabaseCluster.get" title="Permalink to this definition">¶</a></dt>
<dd><p>Get an existing DatabaseCluster resource’s state with the given name, id, and optional extra
properties used to qualify the lookup.</p>
<dl class="field-list simple">
<dt class="field-odd">Parameters</dt>
<dd class="field-odd"><ul class="simple">
<li><p><strong>resource_name</strong> (<em>str</em>) – The unique name of the resulting resource.</p></li>
<li><p><strong>id</strong> (<em>str</em>) – The unique provider ID of the resource to lookup.</p></li>
<li><p><strong>opts</strong> (<a class="reference internal" href="../pulumi/#pulumi.ResourceOptions" title="pulumi.ResourceOptions"><em>pulumi.ResourceOptions</em></a>) – Options for the resource.</p></li>
<li><p><strong>database</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – Name of the cluster’s default database.</p></li>
<li><p><strong>engine</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – Database engine used by the cluster (ex. <code class="docutils literal notranslate"><span class="pre">pg</span></code> for PostreSQL, <code class="docutils literal notranslate"><span class="pre">mysql</span></code> for MySQL, or <code class="docutils literal notranslate"><span class="pre">redis</span></code> for Redis).</p></li>
<li><p><strong>eviction_policy</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – A string specifying the eviction policy for a Redis cluster. Valid values are: <code class="docutils literal notranslate"><span class="pre">noeviction</span></code>, <code class="docutils literal notranslate"><span class="pre">allkeys_lru</span></code>, <code class="docutils literal notranslate"><span class="pre">allkeys_random</span></code>, <code class="docutils literal notranslate"><span class="pre">volatile_lru</span></code>, <code class="docutils literal notranslate"><span class="pre">volatile_random</span></code>, or <code class="docutils literal notranslate"><span class="pre">volatile_ttl</span></code>.</p></li>
<li><p><strong>host</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – Database cluster’s hostname.</p></li>
<li><p><strong>maintenance_windows</strong> (<em>pulumi.Input</em><em>[</em><em>list</em><em>]</em>) – Defines when the automatic maintenance should be performed for the database cluster.</p></li>
<li><p><strong>name</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – The name of the database cluster.</p></li>
<li><p><strong>node_count</strong> (<em>pulumi.Input</em><em>[</em><em>float</em><em>]</em>) – Number of nodes that will be included in the cluster.</p></li>
<li><p><strong>password</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – Password for the cluster’s default user.</p></li>
<li><p><strong>port</strong> (<em>pulumi.Input</em><em>[</em><em>float</em><em>]</em>) – Network port that the database cluster is listening on.</p></li>
<li><p><strong>private_host</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – Same as <code class="docutils literal notranslate"><span class="pre">host</span></code>, but only accessible from resources within the account and in the same region.</p></li>
<li><p><strong>private_network_uuid</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – The ID of the VPC where the database cluster will be located.</p></li>
<li><p><strong>private_uri</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – Same as <code class="docutils literal notranslate"><span class="pre">uri</span></code>, but only accessible from resources within the account and in the same region.</p></li>
<li><p><strong>region</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – DigitalOcean region where the cluster will reside.</p></li>
<li><p><strong>size</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – Database Droplet size associated with the cluster (ex. <code class="docutils literal notranslate"><span class="pre">db-s-1vcpu-1gb</span></code>).</p></li>
<li><p><strong>sql_mode</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – A comma separated string specifying the  SQL modes for a MySQL cluster.</p></li>
<li><p><strong>tags</strong> (<em>pulumi.Input</em><em>[</em><em>list</em><em>]</em>) – A list of tag names to be applied to the database cluster.</p></li>
<li><p><strong>uri</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – The full URI for connecting to the database cluster.</p></li>
<li><p><strong>urn</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – The uniform resource name of the database cluster.</p></li>
<li><p><strong>user</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – Username for the cluster’s default user.</p></li>
<li><p><strong>version</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – Engine version used by the cluster (ex. <code class="docutils literal notranslate"><span class="pre">11</span></code> for PostgreSQL 11).</p></li>
</ul>
</dd>
</dl>
<p>The <strong>maintenance_windows</strong> object supports the following:</p>
<ul class="simple">
<li><p><code class="docutils literal notranslate"><span class="pre">day</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[str]</span></code>) - The day of the week on which to apply maintenance updates.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">hour</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[str]</span></code>) - The hour in UTC at which maintenance updates will be applied in 24 hour format.</p></li>
</ul>
</dd></dl>

<dl class="py method">
<dt id="pulumi_digitalocean.DatabaseCluster.translate_output_property">
<code class="sig-name descname">translate_output_property</code><span class="sig-paren">(</span><em class="sig-param"><span class="n">prop</span></em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_digitalocean.DatabaseCluster.translate_output_property" title="Permalink to this definition">¶</a></dt>
<dd><p>Provides subclasses of Resource an opportunity to translate names of output properties
into a format of their choosing before writing those properties to the resource object.</p>
<dl class="field-list simple">
<dt class="field-odd">Parameters</dt>
<dd class="field-odd"><p><strong>prop</strong> (<em>str</em>) – A property name.</p>
</dd>
<dt class="field-even">Returns</dt>
<dd class="field-even"><p>A potentially transformed property name.</p>
</dd>
<dt class="field-odd">Return type</dt>
<dd class="field-odd"><p>str</p>
</dd>
</dl>
</dd></dl>

<dl class="py method">
<dt id="pulumi_digitalocean.DatabaseCluster.translate_input_property">
<code class="sig-name descname">translate_input_property</code><span class="sig-paren">(</span><em class="sig-param"><span class="n">prop</span></em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_digitalocean.DatabaseCluster.translate_input_property" title="Permalink to this definition">¶</a></dt>
<dd><p>Provides subclasses of Resource an opportunity to translate names of input properties into
a format of their choosing before sending those properties to the Pulumi engine.</p>
<dl class="field-list simple">
<dt class="field-odd">Parameters</dt>
<dd class="field-odd"><p><strong>prop</strong> (<em>str</em>) – A property name.</p>
</dd>
<dt class="field-even">Returns</dt>
<dd class="field-even"><p>A potentially transformed property name.</p>
</dd>
<dt class="field-odd">Return type</dt>
<dd class="field-odd"><p>str</p>
</dd>
</dl>
</dd></dl>

</dd></dl>

<dl class="py class">
<dt id="pulumi_digitalocean.DatabaseConnectionPool">
<em class="property">class </em><code class="sig-prename descclassname">pulumi_digitalocean.</code><code class="sig-name descname">DatabaseConnectionPool</code><span class="sig-paren">(</span><em class="sig-param"><span class="n">resource_name</span></em>, <em class="sig-param"><span class="n">opts</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">cluster_id</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">db_name</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">mode</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">name</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">size</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">user</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">__props__</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">__name__</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">__opts__</span><span class="o">=</span><span class="default_value">None</span></em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_digitalocean.DatabaseConnectionPool" title="Permalink to this definition">¶</a></dt>
<dd><p>Provides a DigitalOcean database connection pool resource.</p>
<div class="highlight-python notranslate"><div class="highlight"><pre><span></span><span class="kn">import</span> <span class="nn">pulumi</span>
<span class="kn">import</span> <span class="nn">pulumi_digitalocean</span> <span class="k">as</span> <span class="nn">digitalocean</span>

<span class="n">postgres_example</span> <span class="o">=</span> <span class="n">digitalocean</span><span class="o">.</span><span class="n">DatabaseCluster</span><span class="p">(</span><span class="s2">&quot;postgres-example&quot;</span><span class="p">,</span>
    <span class="n">engine</span><span class="o">=</span><span class="s2">&quot;pg&quot;</span><span class="p">,</span>
    <span class="n">version</span><span class="o">=</span><span class="s2">&quot;11&quot;</span><span class="p">,</span>
    <span class="n">size</span><span class="o">=</span><span class="s2">&quot;db-s-1vcpu-1gb&quot;</span><span class="p">,</span>
    <span class="n">region</span><span class="o">=</span><span class="s2">&quot;nyc1&quot;</span><span class="p">,</span>
    <span class="n">node_count</span><span class="o">=</span><span class="mi">1</span><span class="p">)</span>
<span class="n">pool_01</span> <span class="o">=</span> <span class="n">digitalocean</span><span class="o">.</span><span class="n">DatabaseConnectionPool</span><span class="p">(</span><span class="s2">&quot;pool-01&quot;</span><span class="p">,</span>
    <span class="n">cluster_id</span><span class="o">=</span><span class="n">postgres_example</span><span class="o">.</span><span class="n">id</span><span class="p">,</span>
    <span class="n">mode</span><span class="o">=</span><span class="s2">&quot;transaction&quot;</span><span class="p">,</span>
    <span class="n">size</span><span class="o">=</span><span class="mi">20</span><span class="p">,</span>
    <span class="n">db_name</span><span class="o">=</span><span class="s2">&quot;defaultdb&quot;</span><span class="p">,</span>
    <span class="n">user</span><span class="o">=</span><span class="s2">&quot;doadmin&quot;</span><span class="p">)</span>
</pre></div>
</div>
<dl class="field-list simple">
<dt class="field-odd">Parameters</dt>
<dd class="field-odd"><ul class="simple">
<li><p><strong>resource_name</strong> (<em>str</em>) – The name of the resource.</p></li>
<li><p><strong>opts</strong> (<a class="reference internal" href="../pulumi/#pulumi.ResourceOptions" title="pulumi.ResourceOptions"><em>pulumi.ResourceOptions</em></a>) – Options for the resource.</p></li>
<li><p><strong>cluster_id</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – The ID of the source database cluster. Note: This must be a PostgreSQL cluster.</p></li>
<li><p><strong>db_name</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – The database for use with the connection pool.</p></li>
<li><p><strong>mode</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – The PGBouncer transaction mode for the connection pool. The allowed values are session, transaction, and statement.</p></li>
<li><p><strong>name</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – The name for the database connection pool.</p></li>
<li><p><strong>size</strong> (<em>pulumi.Input</em><em>[</em><em>float</em><em>]</em>) – The desired size of the PGBouncer connection pool.</p></li>
<li><p><strong>user</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – The name of the database user for use with the connection pool.</p></li>
</ul>
</dd>
</dl>
<dl class="py attribute">
<dt id="pulumi_digitalocean.DatabaseConnectionPool.cluster_id">
<code class="sig-name descname">cluster_id</code><em class="property">: pulumi.Output[str]</em><em class="property"> = None</em><a class="headerlink" href="#pulumi_digitalocean.DatabaseConnectionPool.cluster_id" title="Permalink to this definition">¶</a></dt>
<dd><p>The ID of the source database cluster. Note: This must be a PostgreSQL cluster.</p>
</dd></dl>

<dl class="py attribute">
<dt id="pulumi_digitalocean.DatabaseConnectionPool.db_name">
<code class="sig-name descname">db_name</code><em class="property">: pulumi.Output[str]</em><em class="property"> = None</em><a class="headerlink" href="#pulumi_digitalocean.DatabaseConnectionPool.db_name" title="Permalink to this definition">¶</a></dt>
<dd><p>The database for use with the connection pool.</p>
</dd></dl>

<dl class="py attribute">
<dt id="pulumi_digitalocean.DatabaseConnectionPool.host">
<code class="sig-name descname">host</code><em class="property">: pulumi.Output[str]</em><em class="property"> = None</em><a class="headerlink" href="#pulumi_digitalocean.DatabaseConnectionPool.host" title="Permalink to this definition">¶</a></dt>
<dd><p>The hostname used to connect to the database connection pool.</p>
</dd></dl>

<dl class="py attribute">
<dt id="pulumi_digitalocean.DatabaseConnectionPool.mode">
<code class="sig-name descname">mode</code><em class="property">: pulumi.Output[str]</em><em class="property"> = None</em><a class="headerlink" href="#pulumi_digitalocean.DatabaseConnectionPool.mode" title="Permalink to this definition">¶</a></dt>
<dd><p>The PGBouncer transaction mode for the connection pool. The allowed values are session, transaction, and statement.</p>
</dd></dl>

<dl class="py attribute">
<dt id="pulumi_digitalocean.DatabaseConnectionPool.name">
<code class="sig-name descname">name</code><em class="property">: pulumi.Output[str]</em><em class="property"> = None</em><a class="headerlink" href="#pulumi_digitalocean.DatabaseConnectionPool.name" title="Permalink to this definition">¶</a></dt>
<dd><p>The name for the database connection pool.</p>
</dd></dl>

<dl class="py attribute">
<dt id="pulumi_digitalocean.DatabaseConnectionPool.password">
<code class="sig-name descname">password</code><em class="property">: pulumi.Output[str]</em><em class="property"> = None</em><a class="headerlink" href="#pulumi_digitalocean.DatabaseConnectionPool.password" title="Permalink to this definition">¶</a></dt>
<dd><p>Password for the connection pool’s user.</p>
</dd></dl>

<dl class="py attribute">
<dt id="pulumi_digitalocean.DatabaseConnectionPool.port">
<code class="sig-name descname">port</code><em class="property">: pulumi.Output[float]</em><em class="property"> = None</em><a class="headerlink" href="#pulumi_digitalocean.DatabaseConnectionPool.port" title="Permalink to this definition">¶</a></dt>
<dd><p>Network port that the database connection pool is listening on.</p>
</dd></dl>

<dl class="py attribute">
<dt id="pulumi_digitalocean.DatabaseConnectionPool.private_host">
<code class="sig-name descname">private_host</code><em class="property">: pulumi.Output[str]</em><em class="property"> = None</em><a class="headerlink" href="#pulumi_digitalocean.DatabaseConnectionPool.private_host" title="Permalink to this definition">¶</a></dt>
<dd><p>Same as <code class="docutils literal notranslate"><span class="pre">host</span></code>, but only accessible from resources within the account and in the same region.</p>
</dd></dl>

<dl class="py attribute">
<dt id="pulumi_digitalocean.DatabaseConnectionPool.private_uri">
<code class="sig-name descname">private_uri</code><em class="property">: pulumi.Output[str]</em><em class="property"> = None</em><a class="headerlink" href="#pulumi_digitalocean.DatabaseConnectionPool.private_uri" title="Permalink to this definition">¶</a></dt>
<dd><p>Same as <code class="docutils literal notranslate"><span class="pre">uri</span></code>, but only accessible from resources within the account and in the same region.</p>
</dd></dl>

<dl class="py attribute">
<dt id="pulumi_digitalocean.DatabaseConnectionPool.size">
<code class="sig-name descname">size</code><em class="property">: pulumi.Output[float]</em><em class="property"> = None</em><a class="headerlink" href="#pulumi_digitalocean.DatabaseConnectionPool.size" title="Permalink to this definition">¶</a></dt>
<dd><p>The desired size of the PGBouncer connection pool.</p>
</dd></dl>

<dl class="py attribute">
<dt id="pulumi_digitalocean.DatabaseConnectionPool.uri">
<code class="sig-name descname">uri</code><em class="property">: pulumi.Output[str]</em><em class="property"> = None</em><a class="headerlink" href="#pulumi_digitalocean.DatabaseConnectionPool.uri" title="Permalink to this definition">¶</a></dt>
<dd><p>The full URI for connecting to the database connection pool.</p>
</dd></dl>

<dl class="py attribute">
<dt id="pulumi_digitalocean.DatabaseConnectionPool.user">
<code class="sig-name descname">user</code><em class="property">: pulumi.Output[str]</em><em class="property"> = None</em><a class="headerlink" href="#pulumi_digitalocean.DatabaseConnectionPool.user" title="Permalink to this definition">¶</a></dt>
<dd><p>The name of the database user for use with the connection pool.</p>
</dd></dl>

<dl class="py method">
<dt id="pulumi_digitalocean.DatabaseConnectionPool.get">
<em class="property">static </em><code class="sig-name descname">get</code><span class="sig-paren">(</span><em class="sig-param"><span class="n">resource_name</span></em>, <em class="sig-param"><span class="n">id</span></em>, <em class="sig-param"><span class="n">opts</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">cluster_id</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">db_name</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">host</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">mode</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">name</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">password</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">port</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">private_host</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">private_uri</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">size</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">uri</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">user</span><span class="o">=</span><span class="default_value">None</span></em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_digitalocean.DatabaseConnectionPool.get" title="Permalink to this definition">¶</a></dt>
<dd><p>Get an existing DatabaseConnectionPool resource’s state with the given name, id, and optional extra
properties used to qualify the lookup.</p>
<dl class="field-list simple">
<dt class="field-odd">Parameters</dt>
<dd class="field-odd"><ul class="simple">
<li><p><strong>resource_name</strong> (<em>str</em>) – The unique name of the resulting resource.</p></li>
<li><p><strong>id</strong> (<em>str</em>) – The unique provider ID of the resource to lookup.</p></li>
<li><p><strong>opts</strong> (<a class="reference internal" href="../pulumi/#pulumi.ResourceOptions" title="pulumi.ResourceOptions"><em>pulumi.ResourceOptions</em></a>) – Options for the resource.</p></li>
<li><p><strong>cluster_id</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – The ID of the source database cluster. Note: This must be a PostgreSQL cluster.</p></li>
<li><p><strong>db_name</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – The database for use with the connection pool.</p></li>
<li><p><strong>host</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – The hostname used to connect to the database connection pool.</p></li>
<li><p><strong>mode</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – The PGBouncer transaction mode for the connection pool. The allowed values are session, transaction, and statement.</p></li>
<li><p><strong>name</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – The name for the database connection pool.</p></li>
<li><p><strong>password</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – Password for the connection pool’s user.</p></li>
<li><p><strong>port</strong> (<em>pulumi.Input</em><em>[</em><em>float</em><em>]</em>) – Network port that the database connection pool is listening on.</p></li>
<li><p><strong>private_host</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – Same as <code class="docutils literal notranslate"><span class="pre">host</span></code>, but only accessible from resources within the account and in the same region.</p></li>
<li><p><strong>private_uri</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – Same as <code class="docutils literal notranslate"><span class="pre">uri</span></code>, but only accessible from resources within the account and in the same region.</p></li>
<li><p><strong>size</strong> (<em>pulumi.Input</em><em>[</em><em>float</em><em>]</em>) – The desired size of the PGBouncer connection pool.</p></li>
<li><p><strong>uri</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – The full URI for connecting to the database connection pool.</p></li>
<li><p><strong>user</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – The name of the database user for use with the connection pool.</p></li>
</ul>
</dd>
</dl>
</dd></dl>

<dl class="py method">
<dt id="pulumi_digitalocean.DatabaseConnectionPool.translate_output_property">
<code class="sig-name descname">translate_output_property</code><span class="sig-paren">(</span><em class="sig-param"><span class="n">prop</span></em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_digitalocean.DatabaseConnectionPool.translate_output_property" title="Permalink to this definition">¶</a></dt>
<dd><p>Provides subclasses of Resource an opportunity to translate names of output properties
into a format of their choosing before writing those properties to the resource object.</p>
<dl class="field-list simple">
<dt class="field-odd">Parameters</dt>
<dd class="field-odd"><p><strong>prop</strong> (<em>str</em>) – A property name.</p>
</dd>
<dt class="field-even">Returns</dt>
<dd class="field-even"><p>A potentially transformed property name.</p>
</dd>
<dt class="field-odd">Return type</dt>
<dd class="field-odd"><p>str</p>
</dd>
</dl>
</dd></dl>

<dl class="py method">
<dt id="pulumi_digitalocean.DatabaseConnectionPool.translate_input_property">
<code class="sig-name descname">translate_input_property</code><span class="sig-paren">(</span><em class="sig-param"><span class="n">prop</span></em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_digitalocean.DatabaseConnectionPool.translate_input_property" title="Permalink to this definition">¶</a></dt>
<dd><p>Provides subclasses of Resource an opportunity to translate names of input properties into
a format of their choosing before sending those properties to the Pulumi engine.</p>
<dl class="field-list simple">
<dt class="field-odd">Parameters</dt>
<dd class="field-odd"><p><strong>prop</strong> (<em>str</em>) – A property name.</p>
</dd>
<dt class="field-even">Returns</dt>
<dd class="field-even"><p>A potentially transformed property name.</p>
</dd>
<dt class="field-odd">Return type</dt>
<dd class="field-odd"><p>str</p>
</dd>
</dl>
</dd></dl>

</dd></dl>

<dl class="py class">
<dt id="pulumi_digitalocean.DatabaseDb">
<em class="property">class </em><code class="sig-prename descclassname">pulumi_digitalocean.</code><code class="sig-name descname">DatabaseDb</code><span class="sig-paren">(</span><em class="sig-param"><span class="n">resource_name</span></em>, <em class="sig-param"><span class="n">opts</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">cluster_id</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">name</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">__props__</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">__name__</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">__opts__</span><span class="o">=</span><span class="default_value">None</span></em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_digitalocean.DatabaseDb" title="Permalink to this definition">¶</a></dt>
<dd><p>Provides a DigitalOcean database resource. When creating a new database cluster, a default database with name <code class="docutils literal notranslate"><span class="pre">defaultdb</span></code> will be created. Then, this resource can be used to provide additional database inside the cluster.</p>
<div class="highlight-python notranslate"><div class="highlight"><pre><span></span><span class="kn">import</span> <span class="nn">pulumi</span>
<span class="kn">import</span> <span class="nn">pulumi_digitalocean</span> <span class="k">as</span> <span class="nn">digitalocean</span>

<span class="n">postgres_example</span> <span class="o">=</span> <span class="n">digitalocean</span><span class="o">.</span><span class="n">DatabaseCluster</span><span class="p">(</span><span class="s2">&quot;postgres-example&quot;</span><span class="p">,</span>
    <span class="n">engine</span><span class="o">=</span><span class="s2">&quot;pg&quot;</span><span class="p">,</span>
    <span class="n">version</span><span class="o">=</span><span class="s2">&quot;11&quot;</span><span class="p">,</span>
    <span class="n">size</span><span class="o">=</span><span class="s2">&quot;db-s-1vcpu-1gb&quot;</span><span class="p">,</span>
    <span class="n">region</span><span class="o">=</span><span class="s2">&quot;nyc1&quot;</span><span class="p">,</span>
    <span class="n">node_count</span><span class="o">=</span><span class="mi">1</span><span class="p">)</span>
<span class="n">database_example</span> <span class="o">=</span> <span class="n">digitalocean</span><span class="o">.</span><span class="n">DatabaseDb</span><span class="p">(</span><span class="s2">&quot;database-example&quot;</span><span class="p">,</span> <span class="n">cluster_id</span><span class="o">=</span><span class="n">postgres_example</span><span class="o">.</span><span class="n">id</span><span class="p">)</span>
</pre></div>
</div>
<dl class="field-list simple">
<dt class="field-odd">Parameters</dt>
<dd class="field-odd"><ul class="simple">
<li><p><strong>resource_name</strong> (<em>str</em>) – The name of the resource.</p></li>
<li><p><strong>opts</strong> (<a class="reference internal" href="../pulumi/#pulumi.ResourceOptions" title="pulumi.ResourceOptions"><em>pulumi.ResourceOptions</em></a>) – Options for the resource.</p></li>
<li><p><strong>cluster_id</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – The ID of the original source database cluster.</p></li>
<li><p><strong>name</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – The name for the database.</p></li>
</ul>
</dd>
</dl>
<dl class="py attribute">
<dt id="pulumi_digitalocean.DatabaseDb.cluster_id">
<code class="sig-name descname">cluster_id</code><em class="property">: pulumi.Output[str]</em><em class="property"> = None</em><a class="headerlink" href="#pulumi_digitalocean.DatabaseDb.cluster_id" title="Permalink to this definition">¶</a></dt>
<dd><p>The ID of the original source database cluster.</p>
</dd></dl>

<dl class="py attribute">
<dt id="pulumi_digitalocean.DatabaseDb.name">
<code class="sig-name descname">name</code><em class="property">: pulumi.Output[str]</em><em class="property"> = None</em><a class="headerlink" href="#pulumi_digitalocean.DatabaseDb.name" title="Permalink to this definition">¶</a></dt>
<dd><p>The name for the database.</p>
</dd></dl>

<dl class="py method">
<dt id="pulumi_digitalocean.DatabaseDb.get">
<em class="property">static </em><code class="sig-name descname">get</code><span class="sig-paren">(</span><em class="sig-param"><span class="n">resource_name</span></em>, <em class="sig-param"><span class="n">id</span></em>, <em class="sig-param"><span class="n">opts</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">cluster_id</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">name</span><span class="o">=</span><span class="default_value">None</span></em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_digitalocean.DatabaseDb.get" title="Permalink to this definition">¶</a></dt>
<dd><p>Get an existing DatabaseDb resource’s state with the given name, id, and optional extra
properties used to qualify the lookup.</p>
<dl class="field-list simple">
<dt class="field-odd">Parameters</dt>
<dd class="field-odd"><ul class="simple">
<li><p><strong>resource_name</strong> (<em>str</em>) – The unique name of the resulting resource.</p></li>
<li><p><strong>id</strong> (<em>str</em>) – The unique provider ID of the resource to lookup.</p></li>
<li><p><strong>opts</strong> (<a class="reference internal" href="../pulumi/#pulumi.ResourceOptions" title="pulumi.ResourceOptions"><em>pulumi.ResourceOptions</em></a>) – Options for the resource.</p></li>
<li><p><strong>cluster_id</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – The ID of the original source database cluster.</p></li>
<li><p><strong>name</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – The name for the database.</p></li>
</ul>
</dd>
</dl>
</dd></dl>

<dl class="py method">
<dt id="pulumi_digitalocean.DatabaseDb.translate_output_property">
<code class="sig-name descname">translate_output_property</code><span class="sig-paren">(</span><em class="sig-param"><span class="n">prop</span></em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_digitalocean.DatabaseDb.translate_output_property" title="Permalink to this definition">¶</a></dt>
<dd><p>Provides subclasses of Resource an opportunity to translate names of output properties
into a format of their choosing before writing those properties to the resource object.</p>
<dl class="field-list simple">
<dt class="field-odd">Parameters</dt>
<dd class="field-odd"><p><strong>prop</strong> (<em>str</em>) – A property name.</p>
</dd>
<dt class="field-even">Returns</dt>
<dd class="field-even"><p>A potentially transformed property name.</p>
</dd>
<dt class="field-odd">Return type</dt>
<dd class="field-odd"><p>str</p>
</dd>
</dl>
</dd></dl>

<dl class="py method">
<dt id="pulumi_digitalocean.DatabaseDb.translate_input_property">
<code class="sig-name descname">translate_input_property</code><span class="sig-paren">(</span><em class="sig-param"><span class="n">prop</span></em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_digitalocean.DatabaseDb.translate_input_property" title="Permalink to this definition">¶</a></dt>
<dd><p>Provides subclasses of Resource an opportunity to translate names of input properties into
a format of their choosing before sending those properties to the Pulumi engine.</p>
<dl class="field-list simple">
<dt class="field-odd">Parameters</dt>
<dd class="field-odd"><p><strong>prop</strong> (<em>str</em>) – A property name.</p>
</dd>
<dt class="field-even">Returns</dt>
<dd class="field-even"><p>A potentially transformed property name.</p>
</dd>
<dt class="field-odd">Return type</dt>
<dd class="field-odd"><p>str</p>
</dd>
</dl>
</dd></dl>

</dd></dl>

<dl class="py class">
<dt id="pulumi_digitalocean.DatabaseFirewall">
<em class="property">class </em><code class="sig-prename descclassname">pulumi_digitalocean.</code><code class="sig-name descname">DatabaseFirewall</code><span class="sig-paren">(</span><em class="sig-param"><span class="n">resource_name</span></em>, <em class="sig-param"><span class="n">opts</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">cluster_id</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">rules</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">__props__</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">__name__</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">__opts__</span><span class="o">=</span><span class="default_value">None</span></em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_digitalocean.DatabaseFirewall" title="Permalink to this definition">¶</a></dt>
<dd><p>Provides a DigitalOcean database firewall resource allowing you to restrict
connections to your database to trusted sources. You may limit connections to
specific Droplets, Kubernetes clusters, or IP addresses.</p>
<div class="highlight-python notranslate"><div class="highlight"><pre><span></span><span class="kn">import</span> <span class="nn">pulumi</span>
<span class="kn">import</span> <span class="nn">pulumi_digitalocean</span> <span class="k">as</span> <span class="nn">digitalocean</span>

<span class="n">postgres_example</span> <span class="o">=</span> <span class="n">digitalocean</span><span class="o">.</span><span class="n">DatabaseCluster</span><span class="p">(</span><span class="s2">&quot;postgres-example&quot;</span><span class="p">,</span>
    <span class="n">engine</span><span class="o">=</span><span class="s2">&quot;pg&quot;</span><span class="p">,</span>
    <span class="n">version</span><span class="o">=</span><span class="s2">&quot;11&quot;</span><span class="p">,</span>
    <span class="n">size</span><span class="o">=</span><span class="s2">&quot;db-s-1vcpu-1gb&quot;</span><span class="p">,</span>
    <span class="n">region</span><span class="o">=</span><span class="s2">&quot;nyc1&quot;</span><span class="p">,</span>
    <span class="n">node_count</span><span class="o">=</span><span class="mi">1</span><span class="p">)</span>
<span class="n">example_fw</span> <span class="o">=</span> <span class="n">digitalocean</span><span class="o">.</span><span class="n">DatabaseFirewall</span><span class="p">(</span><span class="s2">&quot;example-fw&quot;</span><span class="p">,</span>
    <span class="n">cluster_id</span><span class="o">=</span><span class="n">postgres_example</span><span class="o">.</span><span class="n">id</span><span class="p">,</span>
    <span class="n">rule</span><span class="o">=</span><span class="p">[</span>
        <span class="p">{</span>
            <span class="s2">&quot;type&quot;</span><span class="p">:</span> <span class="s2">&quot;ip_addr&quot;</span><span class="p">,</span>
            <span class="s2">&quot;value&quot;</span><span class="p">:</span> <span class="s2">&quot;192.168.1.1&quot;</span><span class="p">,</span>
        <span class="p">},</span>
        <span class="p">{</span>
            <span class="s2">&quot;type&quot;</span><span class="p">:</span> <span class="s2">&quot;ip_addr&quot;</span><span class="p">,</span>
            <span class="s2">&quot;value&quot;</span><span class="p">:</span> <span class="s2">&quot;192.0.2.0&quot;</span><span class="p">,</span>
        <span class="p">},</span>
    <span class="p">])</span>
</pre></div>
</div>
<div class="highlight-python notranslate"><div class="highlight"><pre><span></span><span class="kn">import</span> <span class="nn">pulumi</span>
<span class="kn">import</span> <span class="nn">pulumi_digitalocean</span> <span class="k">as</span> <span class="nn">digitalocean</span>

<span class="n">web</span> <span class="o">=</span> <span class="n">digitalocean</span><span class="o">.</span><span class="n">Droplet</span><span class="p">(</span><span class="s2">&quot;web&quot;</span><span class="p">,</span>
    <span class="n">size</span><span class="o">=</span><span class="s2">&quot;s-1vcpu-1gb&quot;</span><span class="p">,</span>
    <span class="n">image</span><span class="o">=</span><span class="s2">&quot;centos-7-x64&quot;</span><span class="p">,</span>
    <span class="n">region</span><span class="o">=</span><span class="s2">&quot;nyc3&quot;</span><span class="p">)</span>
<span class="n">postgres_example</span> <span class="o">=</span> <span class="n">digitalocean</span><span class="o">.</span><span class="n">DatabaseCluster</span><span class="p">(</span><span class="s2">&quot;postgres-example&quot;</span><span class="p">,</span>
    <span class="n">engine</span><span class="o">=</span><span class="s2">&quot;pg&quot;</span><span class="p">,</span>
    <span class="n">version</span><span class="o">=</span><span class="s2">&quot;11&quot;</span><span class="p">,</span>
    <span class="n">size</span><span class="o">=</span><span class="s2">&quot;db-s-1vcpu-1gb&quot;</span><span class="p">,</span>
    <span class="n">region</span><span class="o">=</span><span class="s2">&quot;nyc1&quot;</span><span class="p">,</span>
    <span class="n">node_count</span><span class="o">=</span><span class="mi">1</span><span class="p">)</span>
<span class="n">example_fw</span> <span class="o">=</span> <span class="n">digitalocean</span><span class="o">.</span><span class="n">DatabaseFirewall</span><span class="p">(</span><span class="s2">&quot;example-fw&quot;</span><span class="p">,</span>
    <span class="n">cluster_id</span><span class="o">=</span><span class="n">postgres_example</span><span class="o">.</span><span class="n">id</span><span class="p">,</span>
    <span class="n">rule</span><span class="o">=</span><span class="p">[{</span>
        <span class="s2">&quot;type&quot;</span><span class="p">:</span> <span class="s2">&quot;droplet&quot;</span><span class="p">,</span>
        <span class="s2">&quot;value&quot;</span><span class="p">:</span> <span class="n">web</span><span class="o">.</span><span class="n">id</span><span class="p">,</span>
    <span class="p">}])</span>
</pre></div>
</div>
<dl class="field-list simple">
<dt class="field-odd">Parameters</dt>
<dd class="field-odd"><ul class="simple">
<li><p><strong>resource_name</strong> (<em>str</em>) – The name of the resource.</p></li>
<li><p><strong>opts</strong> (<a class="reference internal" href="../pulumi/#pulumi.ResourceOptions" title="pulumi.ResourceOptions"><em>pulumi.ResourceOptions</em></a>) – Options for the resource.</p></li>
<li><p><strong>cluster_id</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – The ID of the target database cluster.</p></li>
<li><p><strong>rules</strong> (<em>pulumi.Input</em><em>[</em><em>list</em><em>]</em>) – A rule specifying a resource allowed to access the database cluster. The following arguments must be specified:</p></li>
</ul>
</dd>
</dl>
<div class="highlight-default notranslate"><div class="highlight"><pre><span></span>- `type` - (Required) The type of resource that the firewall rule allows to access the database cluster. The possible values are: `droplet`, `k8s`, `ip_addr`, or `tag`.
- `value` - (Required) The ID of the specific resource, the name of a tag applied to a group of resources, or the IP address that the firewall rule allows to access the database cluster.
</pre></div>
</div>
<p>The <strong>rules</strong> object supports the following:</p>
<ul class="simple">
<li><p><code class="docutils literal notranslate"><span class="pre">created_at</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[str]</span></code>) - The date and time when the firewall rule was created.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">type</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[str]</span></code>)</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">uuid</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[str]</span></code>) - A unique identifier for the firewall rule.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">value</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[str]</span></code>)</p></li>
</ul>
<dl class="py attribute">
<dt id="pulumi_digitalocean.DatabaseFirewall.cluster_id">
<code class="sig-name descname">cluster_id</code><em class="property">: pulumi.Output[str]</em><em class="property"> = None</em><a class="headerlink" href="#pulumi_digitalocean.DatabaseFirewall.cluster_id" title="Permalink to this definition">¶</a></dt>
<dd><p>The ID of the target database cluster.</p>
</dd></dl>

<dl class="py attribute">
<dt id="pulumi_digitalocean.DatabaseFirewall.rules">
<code class="sig-name descname">rules</code><em class="property">: pulumi.Output[list]</em><em class="property"> = None</em><a class="headerlink" href="#pulumi_digitalocean.DatabaseFirewall.rules" title="Permalink to this definition">¶</a></dt>
<dd><p>A rule specifying a resource allowed to access the database cluster. The following arguments must be specified:</p>
<ul class="simple">
<li><p><code class="docutils literal notranslate"><span class="pre">type</span></code> - (Required) The type of resource that the firewall rule allows to access the database cluster. The possible values are: <code class="docutils literal notranslate"><span class="pre">droplet</span></code>, <code class="docutils literal notranslate"><span class="pre">k8s</span></code>, <code class="docutils literal notranslate"><span class="pre">ip_addr</span></code>, or <code class="docutils literal notranslate"><span class="pre">tag</span></code>.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">value</span></code> - (Required) The ID of the specific resource, the name of a tag applied to a group of resources, or the IP address that the firewall rule allows to access the database cluster.</p>
<ul>
<li><p><code class="docutils literal notranslate"><span class="pre">created_at</span></code> (<code class="docutils literal notranslate"><span class="pre">str</span></code>) - The date and time when the firewall rule was created.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">type</span></code> (<code class="docutils literal notranslate"><span class="pre">str</span></code>)</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">uuid</span></code> (<code class="docutils literal notranslate"><span class="pre">str</span></code>) - A unique identifier for the firewall rule.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">value</span></code> (<code class="docutils literal notranslate"><span class="pre">str</span></code>)</p></li>
</ul>
</li>
</ul>
</dd></dl>

<dl class="py method">
<dt id="pulumi_digitalocean.DatabaseFirewall.get">
<em class="property">static </em><code class="sig-name descname">get</code><span class="sig-paren">(</span><em class="sig-param"><span class="n">resource_name</span></em>, <em class="sig-param"><span class="n">id</span></em>, <em class="sig-param"><span class="n">opts</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">cluster_id</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">rules</span><span class="o">=</span><span class="default_value">None</span></em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_digitalocean.DatabaseFirewall.get" title="Permalink to this definition">¶</a></dt>
<dd><p>Get an existing DatabaseFirewall resource’s state with the given name, id, and optional extra
properties used to qualify the lookup.</p>
<dl class="field-list simple">
<dt class="field-odd">Parameters</dt>
<dd class="field-odd"><ul class="simple">
<li><p><strong>resource_name</strong> (<em>str</em>) – The unique name of the resulting resource.</p></li>
<li><p><strong>id</strong> (<em>str</em>) – The unique provider ID of the resource to lookup.</p></li>
<li><p><strong>opts</strong> (<a class="reference internal" href="../pulumi/#pulumi.ResourceOptions" title="pulumi.ResourceOptions"><em>pulumi.ResourceOptions</em></a>) – Options for the resource.</p></li>
<li><p><strong>cluster_id</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – The ID of the target database cluster.</p></li>
<li><p><strong>rules</strong> (<em>pulumi.Input</em><em>[</em><em>list</em><em>]</em>) – A rule specifying a resource allowed to access the database cluster. The following arguments must be specified:</p></li>
</ul>
</dd>
</dl>
<div class="highlight-default notranslate"><div class="highlight"><pre><span></span>- `type` - (Required) The type of resource that the firewall rule allows to access the database cluster. The possible values are: `droplet`, `k8s`, `ip_addr`, or `tag`.
- `value` - (Required) The ID of the specific resource, the name of a tag applied to a group of resources, or the IP address that the firewall rule allows to access the database cluster.
</pre></div>
</div>
<p>The <strong>rules</strong> object supports the following:</p>
<ul class="simple">
<li><p><code class="docutils literal notranslate"><span class="pre">created_at</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[str]</span></code>) - The date and time when the firewall rule was created.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">type</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[str]</span></code>)</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">uuid</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[str]</span></code>) - A unique identifier for the firewall rule.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">value</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[str]</span></code>)</p></li>
</ul>
</dd></dl>

<dl class="py method">
<dt id="pulumi_digitalocean.DatabaseFirewall.translate_output_property">
<code class="sig-name descname">translate_output_property</code><span class="sig-paren">(</span><em class="sig-param"><span class="n">prop</span></em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_digitalocean.DatabaseFirewall.translate_output_property" title="Permalink to this definition">¶</a></dt>
<dd><p>Provides subclasses of Resource an opportunity to translate names of output properties
into a format of their choosing before writing those properties to the resource object.</p>
<dl class="field-list simple">
<dt class="field-odd">Parameters</dt>
<dd class="field-odd"><p><strong>prop</strong> (<em>str</em>) – A property name.</p>
</dd>
<dt class="field-even">Returns</dt>
<dd class="field-even"><p>A potentially transformed property name.</p>
</dd>
<dt class="field-odd">Return type</dt>
<dd class="field-odd"><p>str</p>
</dd>
</dl>
</dd></dl>

<dl class="py method">
<dt id="pulumi_digitalocean.DatabaseFirewall.translate_input_property">
<code class="sig-name descname">translate_input_property</code><span class="sig-paren">(</span><em class="sig-param"><span class="n">prop</span></em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_digitalocean.DatabaseFirewall.translate_input_property" title="Permalink to this definition">¶</a></dt>
<dd><p>Provides subclasses of Resource an opportunity to translate names of input properties into
a format of their choosing before sending those properties to the Pulumi engine.</p>
<dl class="field-list simple">
<dt class="field-odd">Parameters</dt>
<dd class="field-odd"><p><strong>prop</strong> (<em>str</em>) – A property name.</p>
</dd>
<dt class="field-even">Returns</dt>
<dd class="field-even"><p>A potentially transformed property name.</p>
</dd>
<dt class="field-odd">Return type</dt>
<dd class="field-odd"><p>str</p>
</dd>
</dl>
</dd></dl>

</dd></dl>

<dl class="py class">
<dt id="pulumi_digitalocean.DatabaseReplica">
<em class="property">class </em><code class="sig-prename descclassname">pulumi_digitalocean.</code><code class="sig-name descname">DatabaseReplica</code><span class="sig-paren">(</span><em class="sig-param"><span class="n">resource_name</span></em>, <em class="sig-param"><span class="n">opts</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">cluster_id</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">name</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">region</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">size</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">tags</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">__props__</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">__name__</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">__opts__</span><span class="o">=</span><span class="default_value">None</span></em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_digitalocean.DatabaseReplica" title="Permalink to this definition">¶</a></dt>
<dd><p>Provides a DigitalOcean database replica resource.</p>
<div class="highlight-python notranslate"><div class="highlight"><pre><span></span><span class="kn">import</span> <span class="nn">pulumi</span>
<span class="kn">import</span> <span class="nn">pulumi_digitalocean</span> <span class="k">as</span> <span class="nn">digitalocean</span>

<span class="n">postgres_example</span> <span class="o">=</span> <span class="n">digitalocean</span><span class="o">.</span><span class="n">DatabaseCluster</span><span class="p">(</span><span class="s2">&quot;postgres-example&quot;</span><span class="p">,</span>
    <span class="n">engine</span><span class="o">=</span><span class="s2">&quot;pg&quot;</span><span class="p">,</span>
    <span class="n">version</span><span class="o">=</span><span class="s2">&quot;11&quot;</span><span class="p">,</span>
    <span class="n">size</span><span class="o">=</span><span class="s2">&quot;db-s-1vcpu-1gb&quot;</span><span class="p">,</span>
    <span class="n">region</span><span class="o">=</span><span class="s2">&quot;nyc1&quot;</span><span class="p">,</span>
    <span class="n">node_count</span><span class="o">=</span><span class="mi">1</span><span class="p">)</span>
<span class="n">read_replica</span> <span class="o">=</span> <span class="n">digitalocean</span><span class="o">.</span><span class="n">DatabaseReplica</span><span class="p">(</span><span class="s2">&quot;read-replica&quot;</span><span class="p">,</span>
    <span class="n">cluster_id</span><span class="o">=</span><span class="n">postgres_example</span><span class="o">.</span><span class="n">id</span><span class="p">,</span>
    <span class="n">size</span><span class="o">=</span><span class="s2">&quot;db-s-1vcpu-1gb&quot;</span><span class="p">,</span>
    <span class="n">region</span><span class="o">=</span><span class="s2">&quot;nyc1&quot;</span><span class="p">)</span>
</pre></div>
</div>
<dl class="field-list simple">
<dt class="field-odd">Parameters</dt>
<dd class="field-odd"><ul class="simple">
<li><p><strong>resource_name</strong> (<em>str</em>) – The name of the resource.</p></li>
<li><p><strong>opts</strong> (<a class="reference internal" href="../pulumi/#pulumi.ResourceOptions" title="pulumi.ResourceOptions"><em>pulumi.ResourceOptions</em></a>) – Options for the resource.</p></li>
<li><p><strong>cluster_id</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – The ID of the original source database cluster.</p></li>
<li><p><strong>name</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – The name for the database replica.</p></li>
<li><p><strong>region</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – DigitalOcean region where the replica will reside.</p></li>
<li><p><strong>size</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – Database Droplet size associated with the replica (ex. <code class="docutils literal notranslate"><span class="pre">db-s-1vcpu-1gb</span></code>).</p></li>
</ul>
</dd>
</dl>
<dl class="py attribute">
<dt id="pulumi_digitalocean.DatabaseReplica.cluster_id">
<code class="sig-name descname">cluster_id</code><em class="property">: pulumi.Output[str]</em><em class="property"> = None</em><a class="headerlink" href="#pulumi_digitalocean.DatabaseReplica.cluster_id" title="Permalink to this definition">¶</a></dt>
<dd><p>The ID of the original source database cluster.</p>
</dd></dl>

<dl class="py attribute">
<dt id="pulumi_digitalocean.DatabaseReplica.database">
<code class="sig-name descname">database</code><em class="property">: pulumi.Output[str]</em><em class="property"> = None</em><a class="headerlink" href="#pulumi_digitalocean.DatabaseReplica.database" title="Permalink to this definition">¶</a></dt>
<dd><p>Name of the replica’s default database.</p>
</dd></dl>

<dl class="py attribute">
<dt id="pulumi_digitalocean.DatabaseReplica.host">
<code class="sig-name descname">host</code><em class="property">: pulumi.Output[str]</em><em class="property"> = None</em><a class="headerlink" href="#pulumi_digitalocean.DatabaseReplica.host" title="Permalink to this definition">¶</a></dt>
<dd><p>Database replica’s hostname.</p>
</dd></dl>

<dl class="py attribute">
<dt id="pulumi_digitalocean.DatabaseReplica.name">
<code class="sig-name descname">name</code><em class="property">: pulumi.Output[str]</em><em class="property"> = None</em><a class="headerlink" href="#pulumi_digitalocean.DatabaseReplica.name" title="Permalink to this definition">¶</a></dt>
<dd><p>The name for the database replica.</p>
</dd></dl>

<dl class="py attribute">
<dt id="pulumi_digitalocean.DatabaseReplica.password">
<code class="sig-name descname">password</code><em class="property">: pulumi.Output[str]</em><em class="property"> = None</em><a class="headerlink" href="#pulumi_digitalocean.DatabaseReplica.password" title="Permalink to this definition">¶</a></dt>
<dd><p>Password for the replica’s default user.</p>
</dd></dl>

<dl class="py attribute">
<dt id="pulumi_digitalocean.DatabaseReplica.port">
<code class="sig-name descname">port</code><em class="property">: pulumi.Output[float]</em><em class="property"> = None</em><a class="headerlink" href="#pulumi_digitalocean.DatabaseReplica.port" title="Permalink to this definition">¶</a></dt>
<dd><p>Network port that the database replica is listening on.</p>
</dd></dl>

<dl class="py attribute">
<dt id="pulumi_digitalocean.DatabaseReplica.private_host">
<code class="sig-name descname">private_host</code><em class="property">: pulumi.Output[str]</em><em class="property"> = None</em><a class="headerlink" href="#pulumi_digitalocean.DatabaseReplica.private_host" title="Permalink to this definition">¶</a></dt>
<dd><p>Same as <code class="docutils literal notranslate"><span class="pre">host</span></code>, but only accessible from resources within the account and in the same region.</p>
</dd></dl>

<dl class="py attribute">
<dt id="pulumi_digitalocean.DatabaseReplica.private_uri">
<code class="sig-name descname">private_uri</code><em class="property">: pulumi.Output[str]</em><em class="property"> = None</em><a class="headerlink" href="#pulumi_digitalocean.DatabaseReplica.private_uri" title="Permalink to this definition">¶</a></dt>
<dd><p>Same as <code class="docutils literal notranslate"><span class="pre">uri</span></code>, but only accessible from resources within the account and in the same region.</p>
</dd></dl>

<dl class="py attribute">
<dt id="pulumi_digitalocean.DatabaseReplica.region">
<code class="sig-name descname">region</code><em class="property">: pulumi.Output[str]</em><em class="property"> = None</em><a class="headerlink" href="#pulumi_digitalocean.DatabaseReplica.region" title="Permalink to this definition">¶</a></dt>
<dd><p>DigitalOcean region where the replica will reside.</p>
</dd></dl>

<dl class="py attribute">
<dt id="pulumi_digitalocean.DatabaseReplica.size">
<code class="sig-name descname">size</code><em class="property">: pulumi.Output[str]</em><em class="property"> = None</em><a class="headerlink" href="#pulumi_digitalocean.DatabaseReplica.size" title="Permalink to this definition">¶</a></dt>
<dd><p>Database Droplet size associated with the replica (ex. <code class="docutils literal notranslate"><span class="pre">db-s-1vcpu-1gb</span></code>).</p>
</dd></dl>

<dl class="py attribute">
<dt id="pulumi_digitalocean.DatabaseReplica.uri">
<code class="sig-name descname">uri</code><em class="property">: pulumi.Output[str]</em><em class="property"> = None</em><a class="headerlink" href="#pulumi_digitalocean.DatabaseReplica.uri" title="Permalink to this definition">¶</a></dt>
<dd><p>The full URI for connecting to the database replica.</p>
</dd></dl>

<dl class="py attribute">
<dt id="pulumi_digitalocean.DatabaseReplica.user">
<code class="sig-name descname">user</code><em class="property">: pulumi.Output[str]</em><em class="property"> = None</em><a class="headerlink" href="#pulumi_digitalocean.DatabaseReplica.user" title="Permalink to this definition">¶</a></dt>
<dd><p>Username for the replica’s default user.</p>
</dd></dl>

<dl class="py method">
<dt id="pulumi_digitalocean.DatabaseReplica.get">
<em class="property">static </em><code class="sig-name descname">get</code><span class="sig-paren">(</span><em class="sig-param"><span class="n">resource_name</span></em>, <em class="sig-param"><span class="n">id</span></em>, <em class="sig-param"><span class="n">opts</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">cluster_id</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">database</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">host</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">name</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">password</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">port</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">private_host</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">private_uri</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">region</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">size</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">tags</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">uri</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">user</span><span class="o">=</span><span class="default_value">None</span></em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_digitalocean.DatabaseReplica.get" title="Permalink to this definition">¶</a></dt>
<dd><p>Get an existing DatabaseReplica resource’s state with the given name, id, and optional extra
properties used to qualify the lookup.</p>
<dl class="field-list simple">
<dt class="field-odd">Parameters</dt>
<dd class="field-odd"><ul class="simple">
<li><p><strong>resource_name</strong> (<em>str</em>) – The unique name of the resulting resource.</p></li>
<li><p><strong>id</strong> (<em>str</em>) – The unique provider ID of the resource to lookup.</p></li>
<li><p><strong>opts</strong> (<a class="reference internal" href="../pulumi/#pulumi.ResourceOptions" title="pulumi.ResourceOptions"><em>pulumi.ResourceOptions</em></a>) – Options for the resource.</p></li>
<li><p><strong>cluster_id</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – The ID of the original source database cluster.</p></li>
<li><p><strong>database</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – Name of the replica’s default database.</p></li>
<li><p><strong>host</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – Database replica’s hostname.</p></li>
<li><p><strong>name</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – The name for the database replica.</p></li>
<li><p><strong>password</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – Password for the replica’s default user.</p></li>
<li><p><strong>port</strong> (<em>pulumi.Input</em><em>[</em><em>float</em><em>]</em>) – Network port that the database replica is listening on.</p></li>
<li><p><strong>private_host</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – Same as <code class="docutils literal notranslate"><span class="pre">host</span></code>, but only accessible from resources within the account and in the same region.</p></li>
<li><p><strong>private_uri</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – Same as <code class="docutils literal notranslate"><span class="pre">uri</span></code>, but only accessible from resources within the account and in the same region.</p></li>
<li><p><strong>region</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – DigitalOcean region where the replica will reside.</p></li>
<li><p><strong>size</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – Database Droplet size associated with the replica (ex. <code class="docutils literal notranslate"><span class="pre">db-s-1vcpu-1gb</span></code>).</p></li>
<li><p><strong>uri</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – The full URI for connecting to the database replica.</p></li>
<li><p><strong>user</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – Username for the replica’s default user.</p></li>
</ul>
</dd>
</dl>
</dd></dl>

<dl class="py method">
<dt id="pulumi_digitalocean.DatabaseReplica.translate_output_property">
<code class="sig-name descname">translate_output_property</code><span class="sig-paren">(</span><em class="sig-param"><span class="n">prop</span></em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_digitalocean.DatabaseReplica.translate_output_property" title="Permalink to this definition">¶</a></dt>
<dd><p>Provides subclasses of Resource an opportunity to translate names of output properties
into a format of their choosing before writing those properties to the resource object.</p>
<dl class="field-list simple">
<dt class="field-odd">Parameters</dt>
<dd class="field-odd"><p><strong>prop</strong> (<em>str</em>) – A property name.</p>
</dd>
<dt class="field-even">Returns</dt>
<dd class="field-even"><p>A potentially transformed property name.</p>
</dd>
<dt class="field-odd">Return type</dt>
<dd class="field-odd"><p>str</p>
</dd>
</dl>
</dd></dl>

<dl class="py method">
<dt id="pulumi_digitalocean.DatabaseReplica.translate_input_property">
<code class="sig-name descname">translate_input_property</code><span class="sig-paren">(</span><em class="sig-param"><span class="n">prop</span></em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_digitalocean.DatabaseReplica.translate_input_property" title="Permalink to this definition">¶</a></dt>
<dd><p>Provides subclasses of Resource an opportunity to translate names of input properties into
a format of their choosing before sending those properties to the Pulumi engine.</p>
<dl class="field-list simple">
<dt class="field-odd">Parameters</dt>
<dd class="field-odd"><p><strong>prop</strong> (<em>str</em>) – A property name.</p>
</dd>
<dt class="field-even">Returns</dt>
<dd class="field-even"><p>A potentially transformed property name.</p>
</dd>
<dt class="field-odd">Return type</dt>
<dd class="field-odd"><p>str</p>
</dd>
</dl>
</dd></dl>

</dd></dl>

<dl class="py class">
<dt id="pulumi_digitalocean.DatabaseUser">
<em class="property">class </em><code class="sig-prename descclassname">pulumi_digitalocean.</code><code class="sig-name descname">DatabaseUser</code><span class="sig-paren">(</span><em class="sig-param"><span class="n">resource_name</span></em>, <em class="sig-param"><span class="n">opts</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">cluster_id</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">mysql_auth_plugin</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">name</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">__props__</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">__name__</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">__opts__</span><span class="o">=</span><span class="default_value">None</span></em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_digitalocean.DatabaseUser" title="Permalink to this definition">¶</a></dt>
<dd><p>Provides a DigitalOcean database user resource. When creating a new database cluster, a default admin user with name <code class="docutils literal notranslate"><span class="pre">doadmin</span></code> will be created. Then, this resource can be used to provide additional normal users inside the cluster.</p>
<blockquote>
<div><p><strong>NOTE:</strong> Any new users created will always have <code class="docutils literal notranslate"><span class="pre">normal</span></code> role, only the default user that comes with database cluster creation has <code class="docutils literal notranslate"><span class="pre">primary</span></code> role. Additional permissions must be managed manually.</p>
</div></blockquote>
<div class="highlight-python notranslate"><div class="highlight"><pre><span></span><span class="kn">import</span> <span class="nn">pulumi</span>
<span class="kn">import</span> <span class="nn">pulumi_digitalocean</span> <span class="k">as</span> <span class="nn">digitalocean</span>

<span class="n">postgres_example</span> <span class="o">=</span> <span class="n">digitalocean</span><span class="o">.</span><span class="n">DatabaseCluster</span><span class="p">(</span><span class="s2">&quot;postgres-example&quot;</span><span class="p">,</span>
    <span class="n">engine</span><span class="o">=</span><span class="s2">&quot;pg&quot;</span><span class="p">,</span>
    <span class="n">version</span><span class="o">=</span><span class="s2">&quot;11&quot;</span><span class="p">,</span>
    <span class="n">size</span><span class="o">=</span><span class="s2">&quot;db-s-1vcpu-1gb&quot;</span><span class="p">,</span>
    <span class="n">region</span><span class="o">=</span><span class="s2">&quot;nyc1&quot;</span><span class="p">,</span>
    <span class="n">node_count</span><span class="o">=</span><span class="mi">1</span><span class="p">)</span>
<span class="n">user_example</span> <span class="o">=</span> <span class="n">digitalocean</span><span class="o">.</span><span class="n">DatabaseUser</span><span class="p">(</span><span class="s2">&quot;user-example&quot;</span><span class="p">,</span> <span class="n">cluster_id</span><span class="o">=</span><span class="n">postgres_example</span><span class="o">.</span><span class="n">id</span><span class="p">)</span>
</pre></div>
</div>
<dl class="field-list simple">
<dt class="field-odd">Parameters</dt>
<dd class="field-odd"><ul class="simple">
<li><p><strong>resource_name</strong> (<em>str</em>) – The name of the resource.</p></li>
<li><p><strong>opts</strong> (<a class="reference internal" href="../pulumi/#pulumi.ResourceOptions" title="pulumi.ResourceOptions"><em>pulumi.ResourceOptions</em></a>) – Options for the resource.</p></li>
<li><p><strong>cluster_id</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – The ID of the original source database cluster.</p></li>
<li><p><strong>mysql_auth_plugin</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – The authentication method to use for connections to the MySQL user account. The valid values are <code class="docutils literal notranslate"><span class="pre">mysql_native_password</span></code> or <code class="docutils literal notranslate"><span class="pre">caching_sha2_password</span></code> (this is the default).</p></li>
<li><p><strong>name</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – The name for the database user.</p></li>
</ul>
</dd>
</dl>
<dl class="py attribute">
<dt id="pulumi_digitalocean.DatabaseUser.cluster_id">
<code class="sig-name descname">cluster_id</code><em class="property">: pulumi.Output[str]</em><em class="property"> = None</em><a class="headerlink" href="#pulumi_digitalocean.DatabaseUser.cluster_id" title="Permalink to this definition">¶</a></dt>
<dd><p>The ID of the original source database cluster.</p>
</dd></dl>

<dl class="py attribute">
<dt id="pulumi_digitalocean.DatabaseUser.mysql_auth_plugin">
<code class="sig-name descname">mysql_auth_plugin</code><em class="property">: pulumi.Output[str]</em><em class="property"> = None</em><a class="headerlink" href="#pulumi_digitalocean.DatabaseUser.mysql_auth_plugin" title="Permalink to this definition">¶</a></dt>
<dd><p>The authentication method to use for connections to the MySQL user account. The valid values are <code class="docutils literal notranslate"><span class="pre">mysql_native_password</span></code> or <code class="docutils literal notranslate"><span class="pre">caching_sha2_password</span></code> (this is the default).</p>
</dd></dl>

<dl class="py attribute">
<dt id="pulumi_digitalocean.DatabaseUser.name">
<code class="sig-name descname">name</code><em class="property">: pulumi.Output[str]</em><em class="property"> = None</em><a class="headerlink" href="#pulumi_digitalocean.DatabaseUser.name" title="Permalink to this definition">¶</a></dt>
<dd><p>The name for the database user.</p>
</dd></dl>

<dl class="py attribute">
<dt id="pulumi_digitalocean.DatabaseUser.password">
<code class="sig-name descname">password</code><em class="property">: pulumi.Output[str]</em><em class="property"> = None</em><a class="headerlink" href="#pulumi_digitalocean.DatabaseUser.password" title="Permalink to this definition">¶</a></dt>
<dd><p>Password for the database user.</p>
</dd></dl>

<dl class="py attribute">
<dt id="pulumi_digitalocean.DatabaseUser.role">
<code class="sig-name descname">role</code><em class="property">: pulumi.Output[str]</em><em class="property"> = None</em><a class="headerlink" href="#pulumi_digitalocean.DatabaseUser.role" title="Permalink to this definition">¶</a></dt>
<dd><p>Role for the database user. The value will be either “primary” or “normal”.</p>
</dd></dl>

<dl class="py method">
<dt id="pulumi_digitalocean.DatabaseUser.get">
<em class="property">static </em><code class="sig-name descname">get</code><span class="sig-paren">(</span><em class="sig-param"><span class="n">resource_name</span></em>, <em class="sig-param"><span class="n">id</span></em>, <em class="sig-param"><span class="n">opts</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">cluster_id</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">mysql_auth_plugin</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">name</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">password</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">role</span><span class="o">=</span><span class="default_value">None</span></em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_digitalocean.DatabaseUser.get" title="Permalink to this definition">¶</a></dt>
<dd><p>Get an existing DatabaseUser resource’s state with the given name, id, and optional extra
properties used to qualify the lookup.</p>
<dl class="field-list simple">
<dt class="field-odd">Parameters</dt>
<dd class="field-odd"><ul class="simple">
<li><p><strong>resource_name</strong> (<em>str</em>) – The unique name of the resulting resource.</p></li>
<li><p><strong>id</strong> (<em>str</em>) – The unique provider ID of the resource to lookup.</p></li>
<li><p><strong>opts</strong> (<a class="reference internal" href="../pulumi/#pulumi.ResourceOptions" title="pulumi.ResourceOptions"><em>pulumi.ResourceOptions</em></a>) – Options for the resource.</p></li>
<li><p><strong>cluster_id</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – The ID of the original source database cluster.</p></li>
<li><p><strong>mysql_auth_plugin</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – The authentication method to use for connections to the MySQL user account. The valid values are <code class="docutils literal notranslate"><span class="pre">mysql_native_password</span></code> or <code class="docutils literal notranslate"><span class="pre">caching_sha2_password</span></code> (this is the default).</p></li>
<li><p><strong>name</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – The name for the database user.</p></li>
<li><p><strong>password</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – Password for the database user.</p></li>
<li><p><strong>role</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – Role for the database user. The value will be either “primary” or “normal”.</p></li>
</ul>
</dd>
</dl>
</dd></dl>

<dl class="py method">
<dt id="pulumi_digitalocean.DatabaseUser.translate_output_property">
<code class="sig-name descname">translate_output_property</code><span class="sig-paren">(</span><em class="sig-param"><span class="n">prop</span></em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_digitalocean.DatabaseUser.translate_output_property" title="Permalink to this definition">¶</a></dt>
<dd><p>Provides subclasses of Resource an opportunity to translate names of output properties
into a format of their choosing before writing those properties to the resource object.</p>
<dl class="field-list simple">
<dt class="field-odd">Parameters</dt>
<dd class="field-odd"><p><strong>prop</strong> (<em>str</em>) – A property name.</p>
</dd>
<dt class="field-even">Returns</dt>
<dd class="field-even"><p>A potentially transformed property name.</p>
</dd>
<dt class="field-odd">Return type</dt>
<dd class="field-odd"><p>str</p>
</dd>
</dl>
</dd></dl>

<dl class="py method">
<dt id="pulumi_digitalocean.DatabaseUser.translate_input_property">
<code class="sig-name descname">translate_input_property</code><span class="sig-paren">(</span><em class="sig-param"><span class="n">prop</span></em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_digitalocean.DatabaseUser.translate_input_property" title="Permalink to this definition">¶</a></dt>
<dd><p>Provides subclasses of Resource an opportunity to translate names of input properties into
a format of their choosing before sending those properties to the Pulumi engine.</p>
<dl class="field-list simple">
<dt class="field-odd">Parameters</dt>
<dd class="field-odd"><p><strong>prop</strong> (<em>str</em>) – A property name.</p>
</dd>
<dt class="field-even">Returns</dt>
<dd class="field-even"><p>A potentially transformed property name.</p>
</dd>
<dt class="field-odd">Return type</dt>
<dd class="field-odd"><p>str</p>
</dd>
</dl>
</dd></dl>

</dd></dl>

<dl class="py class">
<dt id="pulumi_digitalocean.DnsRecord">
<em class="property">class </em><code class="sig-prename descclassname">pulumi_digitalocean.</code><code class="sig-name descname">DnsRecord</code><span class="sig-paren">(</span><em class="sig-param"><span class="n">resource_name</span></em>, <em class="sig-param"><span class="n">opts</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">domain</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">flags</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">name</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">port</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">priority</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">tag</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">ttl</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">type</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">value</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">weight</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">__props__</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">__name__</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">__opts__</span><span class="o">=</span><span class="default_value">None</span></em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_digitalocean.DnsRecord" title="Permalink to this definition">¶</a></dt>
<dd><p>Provides a DigitalOcean DNS record resource.</p>
<div class="highlight-python notranslate"><div class="highlight"><pre><span></span><span class="kn">import</span> <span class="nn">pulumi</span>
<span class="kn">import</span> <span class="nn">pulumi_digitalocean</span> <span class="k">as</span> <span class="nn">digitalocean</span>

<span class="n">default</span> <span class="o">=</span> <span class="n">digitalocean</span><span class="o">.</span><span class="n">Domain</span><span class="p">(</span><span class="s2">&quot;default&quot;</span><span class="p">,</span> <span class="n">name</span><span class="o">=</span><span class="s2">&quot;example.com&quot;</span><span class="p">)</span>
<span class="c1"># Add an A record to the domain for www.example.com.</span>
<span class="n">www</span> <span class="o">=</span> <span class="n">digitalocean</span><span class="o">.</span><span class="n">DnsRecord</span><span class="p">(</span><span class="s2">&quot;www&quot;</span><span class="p">,</span>
    <span class="n">domain</span><span class="o">=</span><span class="n">default</span><span class="o">.</span><span class="n">name</span><span class="p">,</span>
    <span class="nb">type</span><span class="o">=</span><span class="s2">&quot;A&quot;</span><span class="p">,</span>
    <span class="n">value</span><span class="o">=</span><span class="s2">&quot;192.168.0.11&quot;</span><span class="p">)</span>
<span class="c1"># Add a MX record for the example.com domain itself.</span>
<span class="n">mx</span> <span class="o">=</span> <span class="n">digitalocean</span><span class="o">.</span><span class="n">DnsRecord</span><span class="p">(</span><span class="s2">&quot;mx&quot;</span><span class="p">,</span>
    <span class="n">domain</span><span class="o">=</span><span class="n">default</span><span class="o">.</span><span class="n">name</span><span class="p">,</span>
    <span class="nb">type</span><span class="o">=</span><span class="s2">&quot;MX&quot;</span><span class="p">,</span>
    <span class="n">priority</span><span class="o">=</span><span class="mi">10</span><span class="p">,</span>
    <span class="n">value</span><span class="o">=</span><span class="s2">&quot;mail.example.com.&quot;</span><span class="p">)</span>
<span class="n">pulumi</span><span class="o">.</span><span class="n">export</span><span class="p">(</span><span class="s2">&quot;wwwFqdn&quot;</span><span class="p">,</span> <span class="n">www</span><span class="o">.</span><span class="n">fqdn</span><span class="p">)</span>
<span class="n">pulumi</span><span class="o">.</span><span class="n">export</span><span class="p">(</span><span class="s2">&quot;mxFqdn&quot;</span><span class="p">,</span> <span class="n">mx</span><span class="o">.</span><span class="n">fqdn</span><span class="p">)</span>
</pre></div>
</div>
<dl class="field-list simple">
<dt class="field-odd">Parameters</dt>
<dd class="field-odd"><ul class="simple">
<li><p><strong>resource_name</strong> (<em>str</em>) – The name of the resource.</p></li>
<li><p><strong>opts</strong> (<a class="reference internal" href="../pulumi/#pulumi.ResourceOptions" title="pulumi.ResourceOptions"><em>pulumi.ResourceOptions</em></a>) – Options for the resource.</p></li>
<li><p><strong>domain</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – The domain to add the record to.</p></li>
<li><p><strong>flags</strong> (<em>pulumi.Input</em><em>[</em><em>float</em><em>]</em>) – The flags of the record. Only valid when type is <code class="docutils literal notranslate"><span class="pre">CAA</span></code>. Must be between 0 and 255.</p></li>
<li><p><strong>name</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – The name of the record. Use <code class="docutils literal notranslate"><span class="pre">&#64;</span></code> for records on domain’s name itself.</p></li>
<li><p><strong>port</strong> (<em>pulumi.Input</em><em>[</em><em>float</em><em>]</em>) – The port of the record. Only valid when type is <code class="docutils literal notranslate"><span class="pre">SRV</span></code>.  Must be between 1 and 65535.</p></li>
<li><p><strong>priority</strong> (<em>pulumi.Input</em><em>[</em><em>float</em><em>]</em>) – The priority of the record. Only valid when type is <code class="docutils literal notranslate"><span class="pre">MX</span></code> or <code class="docutils literal notranslate"><span class="pre">SRV</span></code>. Must be between 0 and 65535.</p></li>
<li><p><strong>tag</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – The tag of the record. Only valid when type is <code class="docutils literal notranslate"><span class="pre">CAA</span></code>. Must be one of <code class="docutils literal notranslate"><span class="pre">issue</span></code>, <code class="docutils literal notranslate"><span class="pre">issuewild</span></code>, or <code class="docutils literal notranslate"><span class="pre">iodef</span></code>.</p></li>
<li><p><strong>ttl</strong> (<em>pulumi.Input</em><em>[</em><em>float</em><em>]</em>) – The time to live for the record, in seconds. Must be at least 0.</p></li>
<li><p><strong>type</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – The type of record. Must be one of <code class="docutils literal notranslate"><span class="pre">A</span></code>, <code class="docutils literal notranslate"><span class="pre">AAAA</span></code>, <code class="docutils literal notranslate"><span class="pre">CAA</span></code>, <code class="docutils literal notranslate"><span class="pre">CNAME</span></code>, <code class="docutils literal notranslate"><span class="pre">MX</span></code>, <code class="docutils literal notranslate"><span class="pre">NS</span></code>, <code class="docutils literal notranslate"><span class="pre">TXT</span></code>, or <code class="docutils literal notranslate"><span class="pre">SRV</span></code>.</p></li>
<li><p><strong>value</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – The value of the record.</p></li>
<li><p><strong>weight</strong> (<em>pulumi.Input</em><em>[</em><em>float</em><em>]</em>) – The weight of the record. Only valid when type is <code class="docutils literal notranslate"><span class="pre">SRV</span></code>.  Must be between 0 and 65535.</p></li>
</ul>
</dd>
</dl>
<dl class="py attribute">
<dt id="pulumi_digitalocean.DnsRecord.domain">
<code class="sig-name descname">domain</code><em class="property">: pulumi.Output[str]</em><em class="property"> = None</em><a class="headerlink" href="#pulumi_digitalocean.DnsRecord.domain" title="Permalink to this definition">¶</a></dt>
<dd><p>The domain to add the record to.</p>
</dd></dl>

<dl class="py attribute">
<dt id="pulumi_digitalocean.DnsRecord.flags">
<code class="sig-name descname">flags</code><em class="property">: pulumi.Output[float]</em><em class="property"> = None</em><a class="headerlink" href="#pulumi_digitalocean.DnsRecord.flags" title="Permalink to this definition">¶</a></dt>
<dd><p>The flags of the record. Only valid when type is <code class="docutils literal notranslate"><span class="pre">CAA</span></code>. Must be between 0 and 255.</p>
</dd></dl>

<dl class="py attribute">
<dt id="pulumi_digitalocean.DnsRecord.fqdn">
<code class="sig-name descname">fqdn</code><em class="property">: pulumi.Output[str]</em><em class="property"> = None</em><a class="headerlink" href="#pulumi_digitalocean.DnsRecord.fqdn" title="Permalink to this definition">¶</a></dt>
<dd><p>The FQDN of the record</p>
</dd></dl>

<dl class="py attribute">
<dt id="pulumi_digitalocean.DnsRecord.name">
<code class="sig-name descname">name</code><em class="property">: pulumi.Output[str]</em><em class="property"> = None</em><a class="headerlink" href="#pulumi_digitalocean.DnsRecord.name" title="Permalink to this definition">¶</a></dt>
<dd><p>The name of the record. Use <code class="docutils literal notranslate"><span class="pre">&#64;</span></code> for records on domain’s name itself.</p>
</dd></dl>

<dl class="py attribute">
<dt id="pulumi_digitalocean.DnsRecord.port">
<code class="sig-name descname">port</code><em class="property">: pulumi.Output[float]</em><em class="property"> = None</em><a class="headerlink" href="#pulumi_digitalocean.DnsRecord.port" title="Permalink to this definition">¶</a></dt>
<dd><p>The port of the record. Only valid when type is <code class="docutils literal notranslate"><span class="pre">SRV</span></code>.  Must be between 1 and 65535.</p>
</dd></dl>

<dl class="py attribute">
<dt id="pulumi_digitalocean.DnsRecord.priority">
<code class="sig-name descname">priority</code><em class="property">: pulumi.Output[float]</em><em class="property"> = None</em><a class="headerlink" href="#pulumi_digitalocean.DnsRecord.priority" title="Permalink to this definition">¶</a></dt>
<dd><p>The priority of the record. Only valid when type is <code class="docutils literal notranslate"><span class="pre">MX</span></code> or <code class="docutils literal notranslate"><span class="pre">SRV</span></code>. Must be between 0 and 65535.</p>
</dd></dl>

<dl class="py attribute">
<dt id="pulumi_digitalocean.DnsRecord.tag">
<code class="sig-name descname">tag</code><em class="property">: pulumi.Output[str]</em><em class="property"> = None</em><a class="headerlink" href="#pulumi_digitalocean.DnsRecord.tag" title="Permalink to this definition">¶</a></dt>
<dd><p>The tag of the record. Only valid when type is <code class="docutils literal notranslate"><span class="pre">CAA</span></code>. Must be one of <code class="docutils literal notranslate"><span class="pre">issue</span></code>, <code class="docutils literal notranslate"><span class="pre">issuewild</span></code>, or <code class="docutils literal notranslate"><span class="pre">iodef</span></code>.</p>
</dd></dl>

<dl class="py attribute">
<dt id="pulumi_digitalocean.DnsRecord.ttl">
<code class="sig-name descname">ttl</code><em class="property">: pulumi.Output[float]</em><em class="property"> = None</em><a class="headerlink" href="#pulumi_digitalocean.DnsRecord.ttl" title="Permalink to this definition">¶</a></dt>
<dd><p>The time to live for the record, in seconds. Must be at least 0.</p>
</dd></dl>

<dl class="py attribute">
<dt id="pulumi_digitalocean.DnsRecord.type">
<code class="sig-name descname">type</code><em class="property">: pulumi.Output[str]</em><em class="property"> = None</em><a class="headerlink" href="#pulumi_digitalocean.DnsRecord.type" title="Permalink to this definition">¶</a></dt>
<dd><p>The type of record. Must be one of <code class="docutils literal notranslate"><span class="pre">A</span></code>, <code class="docutils literal notranslate"><span class="pre">AAAA</span></code>, <code class="docutils literal notranslate"><span class="pre">CAA</span></code>, <code class="docutils literal notranslate"><span class="pre">CNAME</span></code>, <code class="docutils literal notranslate"><span class="pre">MX</span></code>, <code class="docutils literal notranslate"><span class="pre">NS</span></code>, <code class="docutils literal notranslate"><span class="pre">TXT</span></code>, or <code class="docutils literal notranslate"><span class="pre">SRV</span></code>.</p>
</dd></dl>

<dl class="py attribute">
<dt id="pulumi_digitalocean.DnsRecord.value">
<code class="sig-name descname">value</code><em class="property">: pulumi.Output[str]</em><em class="property"> = None</em><a class="headerlink" href="#pulumi_digitalocean.DnsRecord.value" title="Permalink to this definition">¶</a></dt>
<dd><p>The value of the record.</p>
</dd></dl>

<dl class="py attribute">
<dt id="pulumi_digitalocean.DnsRecord.weight">
<code class="sig-name descname">weight</code><em class="property">: pulumi.Output[float]</em><em class="property"> = None</em><a class="headerlink" href="#pulumi_digitalocean.DnsRecord.weight" title="Permalink to this definition">¶</a></dt>
<dd><p>The weight of the record. Only valid when type is <code class="docutils literal notranslate"><span class="pre">SRV</span></code>.  Must be between 0 and 65535.</p>
</dd></dl>

<dl class="py method">
<dt id="pulumi_digitalocean.DnsRecord.get">
<em class="property">static </em><code class="sig-name descname">get</code><span class="sig-paren">(</span><em class="sig-param"><span class="n">resource_name</span></em>, <em class="sig-param"><span class="n">id</span></em>, <em class="sig-param"><span class="n">opts</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">domain</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">flags</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">fqdn</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">name</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">port</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">priority</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">tag</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">ttl</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">type</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">value</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">weight</span><span class="o">=</span><span class="default_value">None</span></em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_digitalocean.DnsRecord.get" title="Permalink to this definition">¶</a></dt>
<dd><p>Get an existing DnsRecord resource’s state with the given name, id, and optional extra
properties used to qualify the lookup.</p>
<dl class="field-list simple">
<dt class="field-odd">Parameters</dt>
<dd class="field-odd"><ul class="simple">
<li><p><strong>resource_name</strong> (<em>str</em>) – The unique name of the resulting resource.</p></li>
<li><p><strong>id</strong> (<em>str</em>) – The unique provider ID of the resource to lookup.</p></li>
<li><p><strong>opts</strong> (<a class="reference internal" href="../pulumi/#pulumi.ResourceOptions" title="pulumi.ResourceOptions"><em>pulumi.ResourceOptions</em></a>) – Options for the resource.</p></li>
<li><p><strong>domain</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – The domain to add the record to.</p></li>
<li><p><strong>flags</strong> (<em>pulumi.Input</em><em>[</em><em>float</em><em>]</em>) – The flags of the record. Only valid when type is <code class="docutils literal notranslate"><span class="pre">CAA</span></code>. Must be between 0 and 255.</p></li>
<li><p><strong>fqdn</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – The FQDN of the record</p></li>
<li><p><strong>name</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – The name of the record. Use <code class="docutils literal notranslate"><span class="pre">&#64;</span></code> for records on domain’s name itself.</p></li>
<li><p><strong>port</strong> (<em>pulumi.Input</em><em>[</em><em>float</em><em>]</em>) – The port of the record. Only valid when type is <code class="docutils literal notranslate"><span class="pre">SRV</span></code>.  Must be between 1 and 65535.</p></li>
<li><p><strong>priority</strong> (<em>pulumi.Input</em><em>[</em><em>float</em><em>]</em>) – The priority of the record. Only valid when type is <code class="docutils literal notranslate"><span class="pre">MX</span></code> or <code class="docutils literal notranslate"><span class="pre">SRV</span></code>. Must be between 0 and 65535.</p></li>
<li><p><strong>tag</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – The tag of the record. Only valid when type is <code class="docutils literal notranslate"><span class="pre">CAA</span></code>. Must be one of <code class="docutils literal notranslate"><span class="pre">issue</span></code>, <code class="docutils literal notranslate"><span class="pre">issuewild</span></code>, or <code class="docutils literal notranslate"><span class="pre">iodef</span></code>.</p></li>
<li><p><strong>ttl</strong> (<em>pulumi.Input</em><em>[</em><em>float</em><em>]</em>) – The time to live for the record, in seconds. Must be at least 0.</p></li>
<li><p><strong>type</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – The type of record. Must be one of <code class="docutils literal notranslate"><span class="pre">A</span></code>, <code class="docutils literal notranslate"><span class="pre">AAAA</span></code>, <code class="docutils literal notranslate"><span class="pre">CAA</span></code>, <code class="docutils literal notranslate"><span class="pre">CNAME</span></code>, <code class="docutils literal notranslate"><span class="pre">MX</span></code>, <code class="docutils literal notranslate"><span class="pre">NS</span></code>, <code class="docutils literal notranslate"><span class="pre">TXT</span></code>, or <code class="docutils literal notranslate"><span class="pre">SRV</span></code>.</p></li>
<li><p><strong>value</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – The value of the record.</p></li>
<li><p><strong>weight</strong> (<em>pulumi.Input</em><em>[</em><em>float</em><em>]</em>) – The weight of the record. Only valid when type is <code class="docutils literal notranslate"><span class="pre">SRV</span></code>.  Must be between 0 and 65535.</p></li>
</ul>
</dd>
</dl>
</dd></dl>

<dl class="py method">
<dt id="pulumi_digitalocean.DnsRecord.translate_output_property">
<code class="sig-name descname">translate_output_property</code><span class="sig-paren">(</span><em class="sig-param"><span class="n">prop</span></em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_digitalocean.DnsRecord.translate_output_property" title="Permalink to this definition">¶</a></dt>
<dd><p>Provides subclasses of Resource an opportunity to translate names of output properties
into a format of their choosing before writing those properties to the resource object.</p>
<dl class="field-list simple">
<dt class="field-odd">Parameters</dt>
<dd class="field-odd"><p><strong>prop</strong> (<em>str</em>) – A property name.</p>
</dd>
<dt class="field-even">Returns</dt>
<dd class="field-even"><p>A potentially transformed property name.</p>
</dd>
<dt class="field-odd">Return type</dt>
<dd class="field-odd"><p>str</p>
</dd>
</dl>
</dd></dl>

<dl class="py method">
<dt id="pulumi_digitalocean.DnsRecord.translate_input_property">
<code class="sig-name descname">translate_input_property</code><span class="sig-paren">(</span><em class="sig-param"><span class="n">prop</span></em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_digitalocean.DnsRecord.translate_input_property" title="Permalink to this definition">¶</a></dt>
<dd><p>Provides subclasses of Resource an opportunity to translate names of input properties into
a format of their choosing before sending those properties to the Pulumi engine.</p>
<dl class="field-list simple">
<dt class="field-odd">Parameters</dt>
<dd class="field-odd"><p><strong>prop</strong> (<em>str</em>) – A property name.</p>
</dd>
<dt class="field-even">Returns</dt>
<dd class="field-even"><p>A potentially transformed property name.</p>
</dd>
<dt class="field-odd">Return type</dt>
<dd class="field-odd"><p>str</p>
</dd>
</dl>
</dd></dl>

</dd></dl>

<dl class="py class">
<dt id="pulumi_digitalocean.Domain">
<em class="property">class </em><code class="sig-prename descclassname">pulumi_digitalocean.</code><code class="sig-name descname">Domain</code><span class="sig-paren">(</span><em class="sig-param"><span class="n">resource_name</span></em>, <em class="sig-param"><span class="n">opts</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">ip_address</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">name</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">__props__</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">__name__</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">__opts__</span><span class="o">=</span><span class="default_value">None</span></em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_digitalocean.Domain" title="Permalink to this definition">¶</a></dt>
<dd><p>Provides a DigitalOcean domain resource.</p>
<div class="highlight-python notranslate"><div class="highlight"><pre><span></span><span class="kn">import</span> <span class="nn">pulumi</span>
<span class="kn">import</span> <span class="nn">pulumi_digitalocean</span> <span class="k">as</span> <span class="nn">digitalocean</span>

<span class="c1"># Create a new domain</span>
<span class="n">default</span> <span class="o">=</span> <span class="n">digitalocean</span><span class="o">.</span><span class="n">Domain</span><span class="p">(</span><span class="s2">&quot;default&quot;</span><span class="p">,</span>
    <span class="n">name</span><span class="o">=</span><span class="s2">&quot;example.com&quot;</span><span class="p">,</span>
    <span class="n">ip_address</span><span class="o">=</span><span class="n">digitalocean_droplet</span><span class="p">[</span><span class="s2">&quot;foo&quot;</span><span class="p">][</span><span class="s2">&quot;ipv4_address&quot;</span><span class="p">])</span>
</pre></div>
</div>
<dl class="field-list simple">
<dt class="field-odd">Parameters</dt>
<dd class="field-odd"><ul class="simple">
<li><p><strong>resource_name</strong> (<em>str</em>) – The name of the resource.</p></li>
<li><p><strong>opts</strong> (<a class="reference internal" href="../pulumi/#pulumi.ResourceOptions" title="pulumi.ResourceOptions"><em>pulumi.ResourceOptions</em></a>) – Options for the resource.</p></li>
<li><p><strong>ip_address</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – The IP address of the domain. If specified, this IP
is used to created an initial A record for the domain.</p></li>
<li><p><strong>name</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – The name of the domain</p></li>
</ul>
</dd>
</dl>
<dl class="py attribute">
<dt id="pulumi_digitalocean.Domain.ip_address">
<code class="sig-name descname">ip_address</code><em class="property">: pulumi.Output[str]</em><em class="property"> = None</em><a class="headerlink" href="#pulumi_digitalocean.Domain.ip_address" title="Permalink to this definition">¶</a></dt>
<dd><p>The IP address of the domain. If specified, this IP
is used to created an initial A record for the domain.</p>
</dd></dl>

<dl class="py attribute">
<dt id="pulumi_digitalocean.Domain.name">
<code class="sig-name descname">name</code><em class="property">: pulumi.Output[str]</em><em class="property"> = None</em><a class="headerlink" href="#pulumi_digitalocean.Domain.name" title="Permalink to this definition">¶</a></dt>
<dd><p>The name of the domain</p>
</dd></dl>

<dl class="py attribute">
<dt id="pulumi_digitalocean.Domain.urn">
<code class="sig-name descname">urn</code><em class="property">: pulumi.Output[str]</em><em class="property"> = None</em><a class="headerlink" href="#pulumi_digitalocean.Domain.urn" title="Permalink to this definition">¶</a></dt>
<dd><p>The uniform resource name of the domain</p>
</dd></dl>

<dl class="py method">
<dt id="pulumi_digitalocean.Domain.get">
<em class="property">static </em><code class="sig-name descname">get</code><span class="sig-paren">(</span><em class="sig-param"><span class="n">resource_name</span></em>, <em class="sig-param"><span class="n">id</span></em>, <em class="sig-param"><span class="n">opts</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">ip_address</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">name</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">urn</span><span class="o">=</span><span class="default_value">None</span></em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_digitalocean.Domain.get" title="Permalink to this definition">¶</a></dt>
<dd><p>Get an existing Domain resource’s state with the given name, id, and optional extra
properties used to qualify the lookup.</p>
<dl class="field-list simple">
<dt class="field-odd">Parameters</dt>
<dd class="field-odd"><ul class="simple">
<li><p><strong>resource_name</strong> (<em>str</em>) – The unique name of the resulting resource.</p></li>
<li><p><strong>id</strong> (<em>str</em>) – The unique provider ID of the resource to lookup.</p></li>
<li><p><strong>opts</strong> (<a class="reference internal" href="../pulumi/#pulumi.ResourceOptions" title="pulumi.ResourceOptions"><em>pulumi.ResourceOptions</em></a>) – Options for the resource.</p></li>
<li><p><strong>ip_address</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – The IP address of the domain. If specified, this IP
is used to created an initial A record for the domain.</p></li>
<li><p><strong>name</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – The name of the domain</p></li>
<li><p><strong>urn</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – The uniform resource name of the domain</p></li>
</ul>
</dd>
</dl>
</dd></dl>

<dl class="py method">
<dt id="pulumi_digitalocean.Domain.translate_output_property">
<code class="sig-name descname">translate_output_property</code><span class="sig-paren">(</span><em class="sig-param"><span class="n">prop</span></em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_digitalocean.Domain.translate_output_property" title="Permalink to this definition">¶</a></dt>
<dd><p>Provides subclasses of Resource an opportunity to translate names of output properties
into a format of their choosing before writing those properties to the resource object.</p>
<dl class="field-list simple">
<dt class="field-odd">Parameters</dt>
<dd class="field-odd"><p><strong>prop</strong> (<em>str</em>) – A property name.</p>
</dd>
<dt class="field-even">Returns</dt>
<dd class="field-even"><p>A potentially transformed property name.</p>
</dd>
<dt class="field-odd">Return type</dt>
<dd class="field-odd"><p>str</p>
</dd>
</dl>
</dd></dl>

<dl class="py method">
<dt id="pulumi_digitalocean.Domain.translate_input_property">
<code class="sig-name descname">translate_input_property</code><span class="sig-paren">(</span><em class="sig-param"><span class="n">prop</span></em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_digitalocean.Domain.translate_input_property" title="Permalink to this definition">¶</a></dt>
<dd><p>Provides subclasses of Resource an opportunity to translate names of input properties into
a format of their choosing before sending those properties to the Pulumi engine.</p>
<dl class="field-list simple">
<dt class="field-odd">Parameters</dt>
<dd class="field-odd"><p><strong>prop</strong> (<em>str</em>) – A property name.</p>
</dd>
<dt class="field-even">Returns</dt>
<dd class="field-even"><p>A potentially transformed property name.</p>
</dd>
<dt class="field-odd">Return type</dt>
<dd class="field-odd"><p>str</p>
</dd>
</dl>
</dd></dl>

</dd></dl>

<dl class="py class">
<dt id="pulumi_digitalocean.Droplet">
<em class="property">class </em><code class="sig-prename descclassname">pulumi_digitalocean.</code><code class="sig-name descname">Droplet</code><span class="sig-paren">(</span><em class="sig-param"><span class="n">resource_name</span></em>, <em class="sig-param"><span class="n">opts</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">backups</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">image</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">ipv6</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">monitoring</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">name</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">private_networking</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">region</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">resize_disk</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">size</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">ssh_keys</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">tags</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">user_data</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">volume_ids</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">vpc_uuid</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">__props__</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">__name__</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">__opts__</span><span class="o">=</span><span class="default_value">None</span></em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_digitalocean.Droplet" title="Permalink to this definition">¶</a></dt>
<dd><p>Provides a DigitalOcean Droplet resource. This can be used to create,
modify, and delete Droplets. Droplets also support
<a class="reference external" href="https://www.terraform.io/docs/provisioners/index.html">provisioning</a>.</p>
<div class="highlight-python notranslate"><div class="highlight"><pre><span></span><span class="kn">import</span> <span class="nn">pulumi</span>
<span class="kn">import</span> <span class="nn">pulumi_digitalocean</span> <span class="k">as</span> <span class="nn">digitalocean</span>

<span class="c1"># Create a new Web Droplet in the nyc2 region</span>
<span class="n">web</span> <span class="o">=</span> <span class="n">digitalocean</span><span class="o">.</span><span class="n">Droplet</span><span class="p">(</span><span class="s2">&quot;web&quot;</span><span class="p">,</span>
    <span class="n">image</span><span class="o">=</span><span class="s2">&quot;ubuntu-18-04-x64&quot;</span><span class="p">,</span>
    <span class="n">region</span><span class="o">=</span><span class="s2">&quot;nyc2&quot;</span><span class="p">,</span>
    <span class="n">size</span><span class="o">=</span><span class="s2">&quot;s-1vcpu-1gb&quot;</span><span class="p">)</span>
</pre></div>
</div>
<dl class="field-list simple">
<dt class="field-odd">Parameters</dt>
<dd class="field-odd"><ul class="simple">
<li><p><strong>resource_name</strong> (<em>str</em>) – The name of the resource.</p></li>
<li><p><strong>opts</strong> (<a class="reference internal" href="../pulumi/#pulumi.ResourceOptions" title="pulumi.ResourceOptions"><em>pulumi.ResourceOptions</em></a>) – Options for the resource.</p></li>
<li><p><strong>backups</strong> (<em>pulumi.Input</em><em>[</em><em>bool</em><em>]</em>) – Boolean controlling if backups are made. Defaults to
false.</p></li>
<li><p><strong>image</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – The Droplet image ID or slug.</p></li>
<li><p><strong>ipv6</strong> (<em>pulumi.Input</em><em>[</em><em>bool</em><em>]</em>) – Boolean controlling if IPv6 is enabled. Defaults to false.</p></li>
<li><p><strong>monitoring</strong> (<em>pulumi.Input</em><em>[</em><em>bool</em><em>]</em>) – Boolean controlling whether monitoring agent is installed.
Defaults to false.</p></li>
<li><p><strong>name</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – The Droplet name.</p></li>
<li><p><strong>private_networking</strong> (<em>pulumi.Input</em><em>[</em><em>bool</em><em>]</em>) – Boolean controlling if private networking
is enabled. When VPC is enabled on an account, this will provision the
Droplet inside of your account’s default VPC for the region. Use the
<code class="docutils literal notranslate"><span class="pre">vpc_uuid</span></code> attribute to specify a different VPC.</p></li>
<li><p><strong>region</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – The region to start in.</p></li>
<li><p><strong>resize_disk</strong> (<em>pulumi.Input</em><em>[</em><em>bool</em><em>]</em>) – Boolean controlling whether to increase the disk
size when resizing a Droplet. It defaults to <code class="docutils literal notranslate"><span class="pre">true</span></code>. When set to <code class="docutils literal notranslate"><span class="pre">false</span></code>,
only the Droplet’s RAM and CPU will be resized. <strong>Increasing a Droplet’s disk
size is a permanent change</strong>. Increasing only RAM and CPU is reversible.</p></li>
<li><p><strong>size</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – The unique slug that indentifies the type of Droplet. You can find a list of available slugs on <a class="reference external" href="https://developers.digitalocean.com/documentation/v2/#list-all-sizes">DigitalOcean API documentation</a>.</p></li>
<li><p><strong>ssh_keys</strong> (<em>pulumi.Input</em><em>[</em><em>list</em><em>]</em>) – A list of SSH IDs or fingerprints to enable in
the format <code class="docutils literal notranslate"><span class="pre">[12345,</span> <span class="pre">123456]</span></code>. To retrieve this info, use a tool such
as <code class="docutils literal notranslate"><span class="pre">curl</span></code> with the <a class="reference external" href="https://developers.digitalocean.com/documentation/v2/#ssh-keys">DigitalOcean API</a>,
to retrieve them.</p></li>
<li><p><strong>tags</strong> (<em>pulumi.Input</em><em>[</em><em>list</em><em>]</em>) – A list of the tags to be applied to this Droplet.</p></li>
<li><p><strong>user_data</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – A string of the desired User Data for the Droplet.</p></li>
<li><p><strong>volume_ids</strong> (<em>pulumi.Input</em><em>[</em><em>list</em><em>]</em>) – A list of the IDs of each <a class="reference external" href="https://www.terraform.io/docs/providers/do/r/volume.html">block storage volume</a> to be attached to the Droplet.</p></li>
<li><p><strong>vpc_uuid</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – The ID of the VPC where the Droplet will be located.</p></li>
</ul>
</dd>
</dl>
<dl class="py attribute">
<dt id="pulumi_digitalocean.Droplet.backups">
<code class="sig-name descname">backups</code><em class="property">: pulumi.Output[bool]</em><em class="property"> = None</em><a class="headerlink" href="#pulumi_digitalocean.Droplet.backups" title="Permalink to this definition">¶</a></dt>
<dd><p>Boolean controlling if backups are made. Defaults to
false.</p>
</dd></dl>

<dl class="py attribute">
<dt id="pulumi_digitalocean.Droplet.disk">
<code class="sig-name descname">disk</code><em class="property">: pulumi.Output[float]</em><em class="property"> = None</em><a class="headerlink" href="#pulumi_digitalocean.Droplet.disk" title="Permalink to this definition">¶</a></dt>
<dd><p>The size of the instance’s disk in GB</p>
</dd></dl>

<dl class="py attribute">
<dt id="pulumi_digitalocean.Droplet.image">
<code class="sig-name descname">image</code><em class="property">: pulumi.Output[str]</em><em class="property"> = None</em><a class="headerlink" href="#pulumi_digitalocean.Droplet.image" title="Permalink to this definition">¶</a></dt>
<dd><p>The Droplet image ID or slug.</p>
</dd></dl>

<dl class="py attribute">
<dt id="pulumi_digitalocean.Droplet.ipv4_address">
<code class="sig-name descname">ipv4_address</code><em class="property">: pulumi.Output[str]</em><em class="property"> = None</em><a class="headerlink" href="#pulumi_digitalocean.Droplet.ipv4_address" title="Permalink to this definition">¶</a></dt>
<dd><p>The IPv4 address</p>
</dd></dl>

<dl class="py attribute">
<dt id="pulumi_digitalocean.Droplet.ipv4_address_private">
<code class="sig-name descname">ipv4_address_private</code><em class="property">: pulumi.Output[str]</em><em class="property"> = None</em><a class="headerlink" href="#pulumi_digitalocean.Droplet.ipv4_address_private" title="Permalink to this definition">¶</a></dt>
<dd><p>The private networking IPv4 address</p>
</dd></dl>

<dl class="py attribute">
<dt id="pulumi_digitalocean.Droplet.ipv6">
<code class="sig-name descname">ipv6</code><em class="property">: pulumi.Output[bool]</em><em class="property"> = None</em><a class="headerlink" href="#pulumi_digitalocean.Droplet.ipv6" title="Permalink to this definition">¶</a></dt>
<dd><p>Boolean controlling if IPv6 is enabled. Defaults to false.</p>
</dd></dl>

<dl class="py attribute">
<dt id="pulumi_digitalocean.Droplet.ipv6_address">
<code class="sig-name descname">ipv6_address</code><em class="property">: pulumi.Output[str]</em><em class="property"> = None</em><a class="headerlink" href="#pulumi_digitalocean.Droplet.ipv6_address" title="Permalink to this definition">¶</a></dt>
<dd><p>The IPv6 address</p>
</dd></dl>

<dl class="py attribute">
<dt id="pulumi_digitalocean.Droplet.locked">
<code class="sig-name descname">locked</code><em class="property">: pulumi.Output[bool]</em><em class="property"> = None</em><a class="headerlink" href="#pulumi_digitalocean.Droplet.locked" title="Permalink to this definition">¶</a></dt>
<dd><p>Is the Droplet locked</p>
</dd></dl>

<dl class="py attribute">
<dt id="pulumi_digitalocean.Droplet.monitoring">
<code class="sig-name descname">monitoring</code><em class="property">: pulumi.Output[bool]</em><em class="property"> = None</em><a class="headerlink" href="#pulumi_digitalocean.Droplet.monitoring" title="Permalink to this definition">¶</a></dt>
<dd><p>Boolean controlling whether monitoring agent is installed.
Defaults to false.</p>
</dd></dl>

<dl class="py attribute">
<dt id="pulumi_digitalocean.Droplet.name">
<code class="sig-name descname">name</code><em class="property">: pulumi.Output[str]</em><em class="property"> = None</em><a class="headerlink" href="#pulumi_digitalocean.Droplet.name" title="Permalink to this definition">¶</a></dt>
<dd><p>The Droplet name.</p>
</dd></dl>

<dl class="py attribute">
<dt id="pulumi_digitalocean.Droplet.price_hourly">
<code class="sig-name descname">price_hourly</code><em class="property">: pulumi.Output[float]</em><em class="property"> = None</em><a class="headerlink" href="#pulumi_digitalocean.Droplet.price_hourly" title="Permalink to this definition">¶</a></dt>
<dd><p>Droplet hourly price</p>
</dd></dl>

<dl class="py attribute">
<dt id="pulumi_digitalocean.Droplet.price_monthly">
<code class="sig-name descname">price_monthly</code><em class="property">: pulumi.Output[float]</em><em class="property"> = None</em><a class="headerlink" href="#pulumi_digitalocean.Droplet.price_monthly" title="Permalink to this definition">¶</a></dt>
<dd><p>Droplet monthly price</p>
</dd></dl>

<dl class="py attribute">
<dt id="pulumi_digitalocean.Droplet.private_networking">
<code class="sig-name descname">private_networking</code><em class="property">: pulumi.Output[bool]</em><em class="property"> = None</em><a class="headerlink" href="#pulumi_digitalocean.Droplet.private_networking" title="Permalink to this definition">¶</a></dt>
<dd><p>Boolean controlling if private networking
is enabled. When VPC is enabled on an account, this will provision the
Droplet inside of your account’s default VPC for the region. Use the
<code class="docutils literal notranslate"><span class="pre">vpc_uuid</span></code> attribute to specify a different VPC.</p>
</dd></dl>

<dl class="py attribute">
<dt id="pulumi_digitalocean.Droplet.region">
<code class="sig-name descname">region</code><em class="property">: pulumi.Output[str]</em><em class="property"> = None</em><a class="headerlink" href="#pulumi_digitalocean.Droplet.region" title="Permalink to this definition">¶</a></dt>
<dd><p>The region to start in.</p>
</dd></dl>

<dl class="py attribute">
<dt id="pulumi_digitalocean.Droplet.resize_disk">
<code class="sig-name descname">resize_disk</code><em class="property">: pulumi.Output[bool]</em><em class="property"> = None</em><a class="headerlink" href="#pulumi_digitalocean.Droplet.resize_disk" title="Permalink to this definition">¶</a></dt>
<dd><p>Boolean controlling whether to increase the disk
size when resizing a Droplet. It defaults to <code class="docutils literal notranslate"><span class="pre">true</span></code>. When set to <code class="docutils literal notranslate"><span class="pre">false</span></code>,
only the Droplet’s RAM and CPU will be resized. <strong>Increasing a Droplet’s disk
size is a permanent change</strong>. Increasing only RAM and CPU is reversible.</p>
</dd></dl>

<dl class="py attribute">
<dt id="pulumi_digitalocean.Droplet.size">
<code class="sig-name descname">size</code><em class="property">: pulumi.Output[str]</em><em class="property"> = None</em><a class="headerlink" href="#pulumi_digitalocean.Droplet.size" title="Permalink to this definition">¶</a></dt>
<dd><p>The unique slug that indentifies the type of Droplet. You can find a list of available slugs on <a class="reference external" href="https://developers.digitalocean.com/documentation/v2/#list-all-sizes">DigitalOcean API documentation</a>.</p>
</dd></dl>

<dl class="py attribute">
<dt id="pulumi_digitalocean.Droplet.ssh_keys">
<code class="sig-name descname">ssh_keys</code><em class="property">: pulumi.Output[list]</em><em class="property"> = None</em><a class="headerlink" href="#pulumi_digitalocean.Droplet.ssh_keys" title="Permalink to this definition">¶</a></dt>
<dd><p>A list of SSH IDs or fingerprints to enable in
the format <code class="docutils literal notranslate"><span class="pre">[12345,</span> <span class="pre">123456]</span></code>. To retrieve this info, use a tool such
as <code class="docutils literal notranslate"><span class="pre">curl</span></code> with the <a class="reference external" href="https://developers.digitalocean.com/documentation/v2/#ssh-keys">DigitalOcean API</a>,
to retrieve them.</p>
</dd></dl>

<dl class="py attribute">
<dt id="pulumi_digitalocean.Droplet.status">
<code class="sig-name descname">status</code><em class="property">: pulumi.Output[str]</em><em class="property"> = None</em><a class="headerlink" href="#pulumi_digitalocean.Droplet.status" title="Permalink to this definition">¶</a></dt>
<dd><p>The status of the Droplet</p>
</dd></dl>

<dl class="py attribute">
<dt id="pulumi_digitalocean.Droplet.tags">
<code class="sig-name descname">tags</code><em class="property">: pulumi.Output[list]</em><em class="property"> = None</em><a class="headerlink" href="#pulumi_digitalocean.Droplet.tags" title="Permalink to this definition">¶</a></dt>
<dd><p>A list of the tags to be applied to this Droplet.</p>
</dd></dl>

<dl class="py attribute">
<dt id="pulumi_digitalocean.Droplet.urn">
<code class="sig-name descname">urn</code><em class="property">: pulumi.Output[str]</em><em class="property"> = None</em><a class="headerlink" href="#pulumi_digitalocean.Droplet.urn" title="Permalink to this definition">¶</a></dt>
<dd><p>The uniform resource name of the Droplet</p>
<ul class="simple">
<li><p><code class="docutils literal notranslate"><span class="pre">name</span></code>- The name of the Droplet</p></li>
</ul>
</dd></dl>

<dl class="py attribute">
<dt id="pulumi_digitalocean.Droplet.user_data">
<code class="sig-name descname">user_data</code><em class="property">: pulumi.Output[str]</em><em class="property"> = None</em><a class="headerlink" href="#pulumi_digitalocean.Droplet.user_data" title="Permalink to this definition">¶</a></dt>
<dd><p>A string of the desired User Data for the Droplet.</p>
</dd></dl>

<dl class="py attribute">
<dt id="pulumi_digitalocean.Droplet.vcpus">
<code class="sig-name descname">vcpus</code><em class="property">: pulumi.Output[float]</em><em class="property"> = None</em><a class="headerlink" href="#pulumi_digitalocean.Droplet.vcpus" title="Permalink to this definition">¶</a></dt>
<dd><p>The number of the instance’s virtual CPUs</p>
</dd></dl>

<dl class="py attribute">
<dt id="pulumi_digitalocean.Droplet.volume_ids">
<code class="sig-name descname">volume_ids</code><em class="property">: pulumi.Output[list]</em><em class="property"> = None</em><a class="headerlink" href="#pulumi_digitalocean.Droplet.volume_ids" title="Permalink to this definition">¶</a></dt>
<dd><p>A list of the IDs of each <a class="reference external" href="https://www.terraform.io/docs/providers/do/r/volume.html">block storage volume</a> to be attached to the Droplet.</p>
</dd></dl>

<dl class="py attribute">
<dt id="pulumi_digitalocean.Droplet.vpc_uuid">
<code class="sig-name descname">vpc_uuid</code><em class="property">: pulumi.Output[str]</em><em class="property"> = None</em><a class="headerlink" href="#pulumi_digitalocean.Droplet.vpc_uuid" title="Permalink to this definition">¶</a></dt>
<dd><p>The ID of the VPC where the Droplet will be located.</p>
</dd></dl>

<dl class="py method">
<dt id="pulumi_digitalocean.Droplet.get">
<em class="property">static </em><code class="sig-name descname">get</code><span class="sig-paren">(</span><em class="sig-param"><span class="n">resource_name</span></em>, <em class="sig-param"><span class="n">id</span></em>, <em class="sig-param"><span class="n">opts</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">backups</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">created_at</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">disk</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">image</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">ipv4_address</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">ipv4_address_private</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">ipv6</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">ipv6_address</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">locked</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">memory</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">monitoring</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">name</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">price_hourly</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">price_monthly</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">private_networking</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">region</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">resize_disk</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">size</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">ssh_keys</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">status</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">tags</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">urn</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">user_data</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">vcpus</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">volume_ids</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">vpc_uuid</span><span class="o">=</span><span class="default_value">None</span></em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_digitalocean.Droplet.get" title="Permalink to this definition">¶</a></dt>
<dd><p>Get an existing Droplet resource’s state with the given name, id, and optional extra
properties used to qualify the lookup.</p>
<dl class="field-list simple">
<dt class="field-odd">Parameters</dt>
<dd class="field-odd"><ul class="simple">
<li><p><strong>resource_name</strong> (<em>str</em>) – The unique name of the resulting resource.</p></li>
<li><p><strong>id</strong> (<em>str</em>) – The unique provider ID of the resource to lookup.</p></li>
<li><p><strong>opts</strong> (<a class="reference internal" href="../pulumi/#pulumi.ResourceOptions" title="pulumi.ResourceOptions"><em>pulumi.ResourceOptions</em></a>) – Options for the resource.</p></li>
<li><p><strong>backups</strong> (<em>pulumi.Input</em><em>[</em><em>bool</em><em>]</em>) – Boolean controlling if backups are made. Defaults to
false.</p></li>
<li><p><strong>disk</strong> (<em>pulumi.Input</em><em>[</em><em>float</em><em>]</em>) – The size of the instance’s disk in GB</p></li>
<li><p><strong>image</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – The Droplet image ID or slug.</p></li>
<li><p><strong>ipv4_address</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – The IPv4 address</p></li>
<li><p><strong>ipv4_address_private</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – The private networking IPv4 address</p></li>
<li><p><strong>ipv6</strong> (<em>pulumi.Input</em><em>[</em><em>bool</em><em>]</em>) – Boolean controlling if IPv6 is enabled. Defaults to false.</p></li>
<li><p><strong>ipv6_address</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – The IPv6 address</p></li>
<li><p><strong>locked</strong> (<em>pulumi.Input</em><em>[</em><em>bool</em><em>]</em>) – Is the Droplet locked</p></li>
<li><p><strong>monitoring</strong> (<em>pulumi.Input</em><em>[</em><em>bool</em><em>]</em>) – Boolean controlling whether monitoring agent is installed.
Defaults to false.</p></li>
<li><p><strong>name</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – The Droplet name.</p></li>
<li><p><strong>price_hourly</strong> (<em>pulumi.Input</em><em>[</em><em>float</em><em>]</em>) – Droplet hourly price</p></li>
<li><p><strong>price_monthly</strong> (<em>pulumi.Input</em><em>[</em><em>float</em><em>]</em>) – Droplet monthly price</p></li>
<li><p><strong>private_networking</strong> (<em>pulumi.Input</em><em>[</em><em>bool</em><em>]</em>) – Boolean controlling if private networking
is enabled. When VPC is enabled on an account, this will provision the
Droplet inside of your account’s default VPC for the region. Use the
<code class="docutils literal notranslate"><span class="pre">vpc_uuid</span></code> attribute to specify a different VPC.</p></li>
<li><p><strong>region</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – The region to start in.</p></li>
<li><p><strong>resize_disk</strong> (<em>pulumi.Input</em><em>[</em><em>bool</em><em>]</em>) – Boolean controlling whether to increase the disk
size when resizing a Droplet. It defaults to <code class="docutils literal notranslate"><span class="pre">true</span></code>. When set to <code class="docutils literal notranslate"><span class="pre">false</span></code>,
only the Droplet’s RAM and CPU will be resized. <strong>Increasing a Droplet’s disk
size is a permanent change</strong>. Increasing only RAM and CPU is reversible.</p></li>
<li><p><strong>size</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – <p>The unique slug that indentifies the type of Droplet. You can find a list of available slugs on <a class="reference external" href="https://developers.digitalocean.com/documentation/v2/#list-all-sizes">DigitalOcean API documentation</a>.</p>
</p></li>
<li><p><strong>ssh_keys</strong> (<em>pulumi.Input</em><em>[</em><em>list</em><em>]</em>) – <p>A list of SSH IDs or fingerprints to enable in
the format <code class="docutils literal notranslate"><span class="pre">[12345,</span> <span class="pre">123456]</span></code>. To retrieve this info, use a tool such
as <code class="docutils literal notranslate"><span class="pre">curl</span></code> with the <a class="reference external" href="https://developers.digitalocean.com/documentation/v2/#ssh-keys">DigitalOcean API</a>,
to retrieve them.</p>
</p></li>
<li><p><strong>status</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – The status of the Droplet</p></li>
<li><p><strong>tags</strong> (<em>pulumi.Input</em><em>[</em><em>list</em><em>]</em>) – A list of the tags to be applied to this Droplet.</p></li>
<li><p><strong>urn</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – The uniform resource name of the Droplet</p></li>
</ul>
</dd>
</dl>
<div class="highlight-default notranslate"><div class="highlight"><pre><span></span>* `name`- The name of the Droplet
</pre></div>
</div>
<dl class="field-list simple">
<dt class="field-odd">Parameters</dt>
<dd class="field-odd"><ul class="simple">
<li><p><strong>user_data</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – A string of the desired User Data for the Droplet.</p></li>
<li><p><strong>vcpus</strong> (<em>pulumi.Input</em><em>[</em><em>float</em><em>]</em>) – The number of the instance’s virtual CPUs</p></li>
<li><p><strong>volume_ids</strong> (<em>pulumi.Input</em><em>[</em><em>list</em><em>]</em>) – <p>A list of the IDs of each <a class="reference external" href="https://www.terraform.io/docs/providers/do/r/volume.html">block storage volume</a> to be attached to the Droplet.</p>
</p></li>
<li><p><strong>vpc_uuid</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – The ID of the VPC where the Droplet will be located.</p></li>
</ul>
</dd>
</dl>
</dd></dl>

<dl class="py method">
<dt id="pulumi_digitalocean.Droplet.translate_output_property">
<code class="sig-name descname">translate_output_property</code><span class="sig-paren">(</span><em class="sig-param"><span class="n">prop</span></em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_digitalocean.Droplet.translate_output_property" title="Permalink to this definition">¶</a></dt>
<dd><p>Provides subclasses of Resource an opportunity to translate names of output properties
into a format of their choosing before writing those properties to the resource object.</p>
<dl class="field-list simple">
<dt class="field-odd">Parameters</dt>
<dd class="field-odd"><p><strong>prop</strong> (<em>str</em>) – A property name.</p>
</dd>
<dt class="field-even">Returns</dt>
<dd class="field-even"><p>A potentially transformed property name.</p>
</dd>
<dt class="field-odd">Return type</dt>
<dd class="field-odd"><p>str</p>
</dd>
</dl>
</dd></dl>

<dl class="py method">
<dt id="pulumi_digitalocean.Droplet.translate_input_property">
<code class="sig-name descname">translate_input_property</code><span class="sig-paren">(</span><em class="sig-param"><span class="n">prop</span></em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_digitalocean.Droplet.translate_input_property" title="Permalink to this definition">¶</a></dt>
<dd><p>Provides subclasses of Resource an opportunity to translate names of input properties into
a format of their choosing before sending those properties to the Pulumi engine.</p>
<dl class="field-list simple">
<dt class="field-odd">Parameters</dt>
<dd class="field-odd"><p><strong>prop</strong> (<em>str</em>) – A property name.</p>
</dd>
<dt class="field-even">Returns</dt>
<dd class="field-even"><p>A potentially transformed property name.</p>
</dd>
<dt class="field-odd">Return type</dt>
<dd class="field-odd"><p>str</p>
</dd>
</dl>
</dd></dl>

</dd></dl>

<dl class="py class">
<dt id="pulumi_digitalocean.DropletSnapshot">
<em class="property">class </em><code class="sig-prename descclassname">pulumi_digitalocean.</code><code class="sig-name descname">DropletSnapshot</code><span class="sig-paren">(</span><em class="sig-param"><span class="n">resource_name</span></em>, <em class="sig-param"><span class="n">opts</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">droplet_id</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">name</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">__props__</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">__name__</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">__opts__</span><span class="o">=</span><span class="default_value">None</span></em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_digitalocean.DropletSnapshot" title="Permalink to this definition">¶</a></dt>
<dd><p>Provides a resource which can be used to create a snapshot from an existing DigitalOcean Droplet.</p>
<div class="highlight-python notranslate"><div class="highlight"><pre><span></span><span class="kn">import</span> <span class="nn">pulumi</span>
<span class="kn">import</span> <span class="nn">pulumi_digitalocean</span> <span class="k">as</span> <span class="nn">digitalocean</span>

<span class="n">web</span> <span class="o">=</span> <span class="n">digitalocean</span><span class="o">.</span><span class="n">Droplet</span><span class="p">(</span><span class="s2">&quot;web&quot;</span><span class="p">,</span>
    <span class="n">size</span><span class="o">=</span><span class="s2">&quot;s-1vcpu-1gb&quot;</span><span class="p">,</span>
    <span class="n">image</span><span class="o">=</span><span class="s2">&quot;centos-7-x64&quot;</span><span class="p">,</span>
    <span class="n">region</span><span class="o">=</span><span class="s2">&quot;nyc3&quot;</span><span class="p">)</span>
<span class="n">web_snapshot</span> <span class="o">=</span> <span class="n">digitalocean</span><span class="o">.</span><span class="n">DropletSnapshot</span><span class="p">(</span><span class="s2">&quot;web-snapshot&quot;</span><span class="p">,</span> <span class="n">droplet_id</span><span class="o">=</span><span class="n">web</span><span class="o">.</span><span class="n">id</span><span class="p">)</span>
</pre></div>
</div>
<dl class="field-list simple">
<dt class="field-odd">Parameters</dt>
<dd class="field-odd"><ul class="simple">
<li><p><strong>resource_name</strong> (<em>str</em>) – The name of the resource.</p></li>
<li><p><strong>opts</strong> (<a class="reference internal" href="../pulumi/#pulumi.ResourceOptions" title="pulumi.ResourceOptions"><em>pulumi.ResourceOptions</em></a>) – Options for the resource.</p></li>
<li><p><strong>droplet_id</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – The ID of the Droplet from which the snapshot will be taken.</p></li>
<li><p><strong>name</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – A name for the Droplet snapshot.</p></li>
</ul>
</dd>
</dl>
<dl class="py attribute">
<dt id="pulumi_digitalocean.DropletSnapshot.created_at">
<code class="sig-name descname">created_at</code><em class="property">: pulumi.Output[str]</em><em class="property"> = None</em><a class="headerlink" href="#pulumi_digitalocean.DropletSnapshot.created_at" title="Permalink to this definition">¶</a></dt>
<dd><p>The date and time the Droplet snapshot was created.</p>
</dd></dl>

<dl class="py attribute">
<dt id="pulumi_digitalocean.DropletSnapshot.droplet_id">
<code class="sig-name descname">droplet_id</code><em class="property">: pulumi.Output[str]</em><em class="property"> = None</em><a class="headerlink" href="#pulumi_digitalocean.DropletSnapshot.droplet_id" title="Permalink to this definition">¶</a></dt>
<dd><p>The ID of the Droplet from which the snapshot will be taken.</p>
</dd></dl>

<dl class="py attribute">
<dt id="pulumi_digitalocean.DropletSnapshot.min_disk_size">
<code class="sig-name descname">min_disk_size</code><em class="property">: pulumi.Output[float]</em><em class="property"> = None</em><a class="headerlink" href="#pulumi_digitalocean.DropletSnapshot.min_disk_size" title="Permalink to this definition">¶</a></dt>
<dd><p>The minimum size in gigabytes required for a Droplet to be created based on this snapshot.</p>
</dd></dl>

<dl class="py attribute">
<dt id="pulumi_digitalocean.DropletSnapshot.name">
<code class="sig-name descname">name</code><em class="property">: pulumi.Output[str]</em><em class="property"> = None</em><a class="headerlink" href="#pulumi_digitalocean.DropletSnapshot.name" title="Permalink to this definition">¶</a></dt>
<dd><p>A name for the Droplet snapshot.</p>
</dd></dl>

<dl class="py attribute">
<dt id="pulumi_digitalocean.DropletSnapshot.regions">
<code class="sig-name descname">regions</code><em class="property">: pulumi.Output[list]</em><em class="property"> = None</em><a class="headerlink" href="#pulumi_digitalocean.DropletSnapshot.regions" title="Permalink to this definition">¶</a></dt>
<dd><p>A list of DigitalOcean region “slugs” indicating where the droplet snapshot is available.</p>
</dd></dl>

<dl class="py attribute">
<dt id="pulumi_digitalocean.DropletSnapshot.size">
<code class="sig-name descname">size</code><em class="property">: pulumi.Output[float]</em><em class="property"> = None</em><a class="headerlink" href="#pulumi_digitalocean.DropletSnapshot.size" title="Permalink to this definition">¶</a></dt>
<dd><p>The billable size of the Droplet snapshot in gigabytes.</p>
</dd></dl>

<dl class="py method">
<dt id="pulumi_digitalocean.DropletSnapshot.get">
<em class="property">static </em><code class="sig-name descname">get</code><span class="sig-paren">(</span><em class="sig-param"><span class="n">resource_name</span></em>, <em class="sig-param"><span class="n">id</span></em>, <em class="sig-param"><span class="n">opts</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">created_at</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">droplet_id</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">min_disk_size</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">name</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">regions</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">size</span><span class="o">=</span><span class="default_value">None</span></em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_digitalocean.DropletSnapshot.get" title="Permalink to this definition">¶</a></dt>
<dd><p>Get an existing DropletSnapshot resource’s state with the given name, id, and optional extra
properties used to qualify the lookup.</p>
<dl class="field-list simple">
<dt class="field-odd">Parameters</dt>
<dd class="field-odd"><ul class="simple">
<li><p><strong>resource_name</strong> (<em>str</em>) – The unique name of the resulting resource.</p></li>
<li><p><strong>id</strong> (<em>str</em>) – The unique provider ID of the resource to lookup.</p></li>
<li><p><strong>opts</strong> (<a class="reference internal" href="../pulumi/#pulumi.ResourceOptions" title="pulumi.ResourceOptions"><em>pulumi.ResourceOptions</em></a>) – Options for the resource.</p></li>
<li><p><strong>created_at</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – The date and time the Droplet snapshot was created.</p></li>
<li><p><strong>droplet_id</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – The ID of the Droplet from which the snapshot will be taken.</p></li>
<li><p><strong>min_disk_size</strong> (<em>pulumi.Input</em><em>[</em><em>float</em><em>]</em>) – The minimum size in gigabytes required for a Droplet to be created based on this snapshot.</p></li>
<li><p><strong>name</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – A name for the Droplet snapshot.</p></li>
<li><p><strong>regions</strong> (<em>pulumi.Input</em><em>[</em><em>list</em><em>]</em>) – A list of DigitalOcean region “slugs” indicating where the droplet snapshot is available.</p></li>
<li><p><strong>size</strong> (<em>pulumi.Input</em><em>[</em><em>float</em><em>]</em>) – The billable size of the Droplet snapshot in gigabytes.</p></li>
</ul>
</dd>
</dl>
</dd></dl>

<dl class="py method">
<dt id="pulumi_digitalocean.DropletSnapshot.translate_output_property">
<code class="sig-name descname">translate_output_property</code><span class="sig-paren">(</span><em class="sig-param"><span class="n">prop</span></em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_digitalocean.DropletSnapshot.translate_output_property" title="Permalink to this definition">¶</a></dt>
<dd><p>Provides subclasses of Resource an opportunity to translate names of output properties
into a format of their choosing before writing those properties to the resource object.</p>
<dl class="field-list simple">
<dt class="field-odd">Parameters</dt>
<dd class="field-odd"><p><strong>prop</strong> (<em>str</em>) – A property name.</p>
</dd>
<dt class="field-even">Returns</dt>
<dd class="field-even"><p>A potentially transformed property name.</p>
</dd>
<dt class="field-odd">Return type</dt>
<dd class="field-odd"><p>str</p>
</dd>
</dl>
</dd></dl>

<dl class="py method">
<dt id="pulumi_digitalocean.DropletSnapshot.translate_input_property">
<code class="sig-name descname">translate_input_property</code><span class="sig-paren">(</span><em class="sig-param"><span class="n">prop</span></em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_digitalocean.DropletSnapshot.translate_input_property" title="Permalink to this definition">¶</a></dt>
<dd><p>Provides subclasses of Resource an opportunity to translate names of input properties into
a format of their choosing before sending those properties to the Pulumi engine.</p>
<dl class="field-list simple">
<dt class="field-odd">Parameters</dt>
<dd class="field-odd"><p><strong>prop</strong> (<em>str</em>) – A property name.</p>
</dd>
<dt class="field-even">Returns</dt>
<dd class="field-even"><p>A potentially transformed property name.</p>
</dd>
<dt class="field-odd">Return type</dt>
<dd class="field-odd"><p>str</p>
</dd>
</dl>
</dd></dl>

</dd></dl>

<dl class="py class">
<dt id="pulumi_digitalocean.Firewall">
<em class="property">class </em><code class="sig-prename descclassname">pulumi_digitalocean.</code><code class="sig-name descname">Firewall</code><span class="sig-paren">(</span><em class="sig-param"><span class="n">resource_name</span></em>, <em class="sig-param"><span class="n">opts</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">droplet_ids</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">inbound_rules</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">name</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">outbound_rules</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">tags</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">__props__</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">__name__</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">__opts__</span><span class="o">=</span><span class="default_value">None</span></em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_digitalocean.Firewall" title="Permalink to this definition">¶</a></dt>
<dd><p>Provides a DigitalOcean Cloud Firewall resource. This can be used to create,
modify, and delete Firewalls.</p>
<div class="highlight-python notranslate"><div class="highlight"><pre><span></span><span class="kn">import</span> <span class="nn">pulumi</span>
<span class="kn">import</span> <span class="nn">pulumi_digitalocean</span> <span class="k">as</span> <span class="nn">digitalocean</span>

<span class="n">web_droplet</span> <span class="o">=</span> <span class="n">digitalocean</span><span class="o">.</span><span class="n">Droplet</span><span class="p">(</span><span class="s2">&quot;webDroplet&quot;</span><span class="p">,</span>
    <span class="n">size</span><span class="o">=</span><span class="s2">&quot;s-1vcpu-1gb&quot;</span><span class="p">,</span>
    <span class="n">image</span><span class="o">=</span><span class="s2">&quot;ubuntu-18-04-x64&quot;</span><span class="p">,</span>
    <span class="n">region</span><span class="o">=</span><span class="s2">&quot;nyc3&quot;</span><span class="p">)</span>
<span class="n">web_firewall</span> <span class="o">=</span> <span class="n">digitalocean</span><span class="o">.</span><span class="n">Firewall</span><span class="p">(</span><span class="s2">&quot;webFirewall&quot;</span><span class="p">,</span>
    <span class="n">droplet_ids</span><span class="o">=</span><span class="p">[</span><span class="n">web_droplet</span><span class="o">.</span><span class="n">id</span><span class="p">],</span>
    <span class="n">inbound_rule</span><span class="o">=</span><span class="p">[</span>
        <span class="p">{</span>
            <span class="s2">&quot;protocol&quot;</span><span class="p">:</span> <span class="s2">&quot;tcp&quot;</span><span class="p">,</span>
            <span class="s2">&quot;portRange&quot;</span><span class="p">:</span> <span class="s2">&quot;22&quot;</span><span class="p">,</span>
            <span class="s2">&quot;sourceAddresses&quot;</span><span class="p">:</span> <span class="p">[</span>
                <span class="s2">&quot;192.168.1.0/24&quot;</span><span class="p">,</span>
                <span class="s2">&quot;2002:1:2::/48&quot;</span><span class="p">,</span>
            <span class="p">],</span>
        <span class="p">},</span>
        <span class="p">{</span>
            <span class="s2">&quot;protocol&quot;</span><span class="p">:</span> <span class="s2">&quot;tcp&quot;</span><span class="p">,</span>
            <span class="s2">&quot;portRange&quot;</span><span class="p">:</span> <span class="s2">&quot;80&quot;</span><span class="p">,</span>
            <span class="s2">&quot;sourceAddresses&quot;</span><span class="p">:</span> <span class="p">[</span>
                <span class="s2">&quot;0.0.0.0/0&quot;</span><span class="p">,</span>
                <span class="s2">&quot;::/0&quot;</span><span class="p">,</span>
            <span class="p">],</span>
        <span class="p">},</span>
        <span class="p">{</span>
            <span class="s2">&quot;protocol&quot;</span><span class="p">:</span> <span class="s2">&quot;tcp&quot;</span><span class="p">,</span>
            <span class="s2">&quot;portRange&quot;</span><span class="p">:</span> <span class="s2">&quot;443&quot;</span><span class="p">,</span>
            <span class="s2">&quot;sourceAddresses&quot;</span><span class="p">:</span> <span class="p">[</span>
                <span class="s2">&quot;0.0.0.0/0&quot;</span><span class="p">,</span>
                <span class="s2">&quot;::/0&quot;</span><span class="p">,</span>
            <span class="p">],</span>
        <span class="p">},</span>
        <span class="p">{</span>
            <span class="s2">&quot;protocol&quot;</span><span class="p">:</span> <span class="s2">&quot;icmp&quot;</span><span class="p">,</span>
            <span class="s2">&quot;sourceAddresses&quot;</span><span class="p">:</span> <span class="p">[</span>
                <span class="s2">&quot;0.0.0.0/0&quot;</span><span class="p">,</span>
                <span class="s2">&quot;::/0&quot;</span><span class="p">,</span>
            <span class="p">],</span>
        <span class="p">},</span>
    <span class="p">],</span>
    <span class="n">outbound_rule</span><span class="o">=</span><span class="p">[</span>
        <span class="p">{</span>
            <span class="s2">&quot;protocol&quot;</span><span class="p">:</span> <span class="s2">&quot;tcp&quot;</span><span class="p">,</span>
            <span class="s2">&quot;portRange&quot;</span><span class="p">:</span> <span class="s2">&quot;53&quot;</span><span class="p">,</span>
            <span class="s2">&quot;destinationAddresses&quot;</span><span class="p">:</span> <span class="p">[</span>
                <span class="s2">&quot;0.0.0.0/0&quot;</span><span class="p">,</span>
                <span class="s2">&quot;::/0&quot;</span><span class="p">,</span>
            <span class="p">],</span>
        <span class="p">},</span>
        <span class="p">{</span>
            <span class="s2">&quot;protocol&quot;</span><span class="p">:</span> <span class="s2">&quot;udp&quot;</span><span class="p">,</span>
            <span class="s2">&quot;portRange&quot;</span><span class="p">:</span> <span class="s2">&quot;53&quot;</span><span class="p">,</span>
            <span class="s2">&quot;destinationAddresses&quot;</span><span class="p">:</span> <span class="p">[</span>
                <span class="s2">&quot;0.0.0.0/0&quot;</span><span class="p">,</span>
                <span class="s2">&quot;::/0&quot;</span><span class="p">,</span>
            <span class="p">],</span>
        <span class="p">},</span>
        <span class="p">{</span>
            <span class="s2">&quot;protocol&quot;</span><span class="p">:</span> <span class="s2">&quot;icmp&quot;</span><span class="p">,</span>
            <span class="s2">&quot;destinationAddresses&quot;</span><span class="p">:</span> <span class="p">[</span>
                <span class="s2">&quot;0.0.0.0/0&quot;</span><span class="p">,</span>
                <span class="s2">&quot;::/0&quot;</span><span class="p">,</span>
            <span class="p">],</span>
        <span class="p">},</span>
    <span class="p">])</span>
</pre></div>
</div>
<dl class="field-list simple">
<dt class="field-odd">Parameters</dt>
<dd class="field-odd"><ul class="simple">
<li><p><strong>resource_name</strong> (<em>str</em>) – The name of the resource.</p></li>
<li><p><strong>opts</strong> (<a class="reference internal" href="../pulumi/#pulumi.ResourceOptions" title="pulumi.ResourceOptions"><em>pulumi.ResourceOptions</em></a>) – Options for the resource.</p></li>
<li><p><strong>droplet_ids</strong> (<em>pulumi.Input</em><em>[</em><em>list</em><em>]</em>) – The list of the IDs of the Droplets assigned
to the Firewall.</p></li>
<li><p><strong>inbound_rules</strong> (<em>pulumi.Input</em><em>[</em><em>list</em><em>]</em>) – The inbound access rule block for the Firewall.
The <code class="docutils literal notranslate"><span class="pre">inbound_rule</span></code> block is documented below.</p></li>
<li><p><strong>name</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – The Firewall name</p></li>
<li><p><strong>outbound_rules</strong> (<em>pulumi.Input</em><em>[</em><em>list</em><em>]</em>) – The outbound access rule block for the Firewall.
The <code class="docutils literal notranslate"><span class="pre">outbound_rule</span></code> block is documented below.</p></li>
<li><p><strong>tags</strong> (<em>pulumi.Input</em><em>[</em><em>list</em><em>]</em>) – The names of the Tags assigned to the Firewall.</p></li>
</ul>
</dd>
</dl>
<p>The <strong>inbound_rules</strong> object supports the following:</p>
<ul class="simple">
<li><p><code class="docutils literal notranslate"><span class="pre">portRange</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[str]</span></code>) - The ports on which traffic will be allowed
specified as a string containing a single port, a range (e.g. “8000-9000”),
or “1-65535” to open all ports for a protocol. Required for when protocol is
<code class="docutils literal notranslate"><span class="pre">tcp</span></code> or <code class="docutils literal notranslate"><span class="pre">udp</span></code>.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">protocol</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[str]</span></code>) - The type of traffic to be allowed.
This may be one of “tcp”, “udp”, or “icmp”.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">sourceAddresses</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[list]</span></code>) - An array of strings containing the IPv4
addresses, IPv6 addresses, IPv4 CIDRs, and/or IPv6 CIDRs from which the
inbound traffic will be accepted.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">sourceDropletIds</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[list]</span></code>) - An array containing the IDs of
the Droplets from which the inbound traffic will be accepted.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">sourceLoadBalancerUids</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[list]</span></code>) - An array containing the IDs
of the Load Balancers from which the inbound traffic will be accepted.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">sourceTags</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[list]</span></code>) - An array containing the names of Tags
corresponding to groups of Droplets from which the inbound traffic
will be accepted.</p></li>
</ul>
<p>The <strong>outbound_rules</strong> object supports the following:</p>
<ul class="simple">
<li><p><code class="docutils literal notranslate"><span class="pre">destinationAddresses</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[list]</span></code>) - An array of strings containing the IPv4
addresses, IPv6 addresses, IPv4 CIDRs, and/or IPv6 CIDRs to which the
outbound traffic will be allowed.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">destinationDropletIds</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[list]</span></code>) - An array containing the IDs of
the Droplets to which the outbound traffic will be allowed.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">destinationLoadBalancerUids</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[list]</span></code>) - An array containing the IDs
of the Load Balancers to which the outbound traffic will be allowed.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">destinationTags</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[list]</span></code>) - An array containing the names of Tags
corresponding to groups of Droplets to which the outbound traffic will
be allowed.
traffic.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">portRange</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[str]</span></code>) - The ports on which traffic will be allowed
specified as a string containing a single port, a range (e.g. “8000-9000”),
or “1-65535” to open all ports for a protocol. Required for when protocol is
<code class="docutils literal notranslate"><span class="pre">tcp</span></code> or <code class="docutils literal notranslate"><span class="pre">udp</span></code>.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">protocol</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[str]</span></code>) - The type of traffic to be allowed.
This may be one of “tcp”, “udp”, or “icmp”.</p></li>
</ul>
<dl class="py attribute">
<dt id="pulumi_digitalocean.Firewall.created_at">
<code class="sig-name descname">created_at</code><em class="property">: pulumi.Output[str]</em><em class="property"> = None</em><a class="headerlink" href="#pulumi_digitalocean.Firewall.created_at" title="Permalink to this definition">¶</a></dt>
<dd><p>A time value given in ISO8601 combined date and time format
that represents when the Firewall was created.</p>
</dd></dl>

<dl class="py attribute">
<dt id="pulumi_digitalocean.Firewall.droplet_ids">
<code class="sig-name descname">droplet_ids</code><em class="property">: pulumi.Output[list]</em><em class="property"> = None</em><a class="headerlink" href="#pulumi_digitalocean.Firewall.droplet_ids" title="Permalink to this definition">¶</a></dt>
<dd><p>The list of the IDs of the Droplets assigned
to the Firewall.</p>
</dd></dl>

<dl class="py attribute">
<dt id="pulumi_digitalocean.Firewall.inbound_rules">
<code class="sig-name descname">inbound_rules</code><em class="property">: pulumi.Output[list]</em><em class="property"> = None</em><a class="headerlink" href="#pulumi_digitalocean.Firewall.inbound_rules" title="Permalink to this definition">¶</a></dt>
<dd><p>The inbound access rule block for the Firewall.
The <code class="docutils literal notranslate"><span class="pre">inbound_rule</span></code> block is documented below.</p>
<ul class="simple">
<li><p><code class="docutils literal notranslate"><span class="pre">portRange</span></code> (<code class="docutils literal notranslate"><span class="pre">str</span></code>) - The ports on which traffic will be allowed
specified as a string containing a single port, a range (e.g. “8000-9000”),
or “1-65535” to open all ports for a protocol. Required for when protocol is
<code class="docutils literal notranslate"><span class="pre">tcp</span></code> or <code class="docutils literal notranslate"><span class="pre">udp</span></code>.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">protocol</span></code> (<code class="docutils literal notranslate"><span class="pre">str</span></code>) - The type of traffic to be allowed.
This may be one of “tcp”, “udp”, or “icmp”.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">sourceAddresses</span></code> (<code class="docutils literal notranslate"><span class="pre">list</span></code>) - An array of strings containing the IPv4
addresses, IPv6 addresses, IPv4 CIDRs, and/or IPv6 CIDRs from which the
inbound traffic will be accepted.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">sourceDropletIds</span></code> (<code class="docutils literal notranslate"><span class="pre">list</span></code>) - An array containing the IDs of
the Droplets from which the inbound traffic will be accepted.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">sourceLoadBalancerUids</span></code> (<code class="docutils literal notranslate"><span class="pre">list</span></code>) - An array containing the IDs
of the Load Balancers from which the inbound traffic will be accepted.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">sourceTags</span></code> (<code class="docutils literal notranslate"><span class="pre">list</span></code>) - An array containing the names of Tags
corresponding to groups of Droplets from which the inbound traffic
will be accepted.</p></li>
</ul>
</dd></dl>

<dl class="py attribute">
<dt id="pulumi_digitalocean.Firewall.name">
<code class="sig-name descname">name</code><em class="property">: pulumi.Output[str]</em><em class="property"> = None</em><a class="headerlink" href="#pulumi_digitalocean.Firewall.name" title="Permalink to this definition">¶</a></dt>
<dd><p>The Firewall name</p>
</dd></dl>

<dl class="py attribute">
<dt id="pulumi_digitalocean.Firewall.outbound_rules">
<code class="sig-name descname">outbound_rules</code><em class="property">: pulumi.Output[list]</em><em class="property"> = None</em><a class="headerlink" href="#pulumi_digitalocean.Firewall.outbound_rules" title="Permalink to this definition">¶</a></dt>
<dd><p>The outbound access rule block for the Firewall.
The <code class="docutils literal notranslate"><span class="pre">outbound_rule</span></code> block is documented below.</p>
<ul class="simple">
<li><p><code class="docutils literal notranslate"><span class="pre">destinationAddresses</span></code> (<code class="docutils literal notranslate"><span class="pre">list</span></code>) - An array of strings containing the IPv4
addresses, IPv6 addresses, IPv4 CIDRs, and/or IPv6 CIDRs to which the
outbound traffic will be allowed.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">destinationDropletIds</span></code> (<code class="docutils literal notranslate"><span class="pre">list</span></code>) - An array containing the IDs of
the Droplets to which the outbound traffic will be allowed.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">destinationLoadBalancerUids</span></code> (<code class="docutils literal notranslate"><span class="pre">list</span></code>) - An array containing the IDs
of the Load Balancers to which the outbound traffic will be allowed.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">destinationTags</span></code> (<code class="docutils literal notranslate"><span class="pre">list</span></code>) - An array containing the names of Tags
corresponding to groups of Droplets to which the outbound traffic will
be allowed.
traffic.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">portRange</span></code> (<code class="docutils literal notranslate"><span class="pre">str</span></code>) - The ports on which traffic will be allowed
specified as a string containing a single port, a range (e.g. “8000-9000”),
or “1-65535” to open all ports for a protocol. Required for when protocol is
<code class="docutils literal notranslate"><span class="pre">tcp</span></code> or <code class="docutils literal notranslate"><span class="pre">udp</span></code>.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">protocol</span></code> (<code class="docutils literal notranslate"><span class="pre">str</span></code>) - The type of traffic to be allowed.
This may be one of “tcp”, “udp”, or “icmp”.</p></li>
</ul>
</dd></dl>

<dl class="py attribute">
<dt id="pulumi_digitalocean.Firewall.pending_changes">
<code class="sig-name descname">pending_changes</code><em class="property">: pulumi.Output[list]</em><em class="property"> = None</em><a class="headerlink" href="#pulumi_digitalocean.Firewall.pending_changes" title="Permalink to this definition">¶</a></dt>
<dd><p>An list of object containing the fields, “droplet_id”,
“removing”, and “status”.  It is provided to detail exactly which Droplets
are having their security policies updated.  When empty, all changes
have been successfully applied.</p>
<ul class="simple">
<li><p><code class="docutils literal notranslate"><span class="pre">droplet_id</span></code> (<code class="docutils literal notranslate"><span class="pre">float</span></code>)</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">removing</span></code> (<code class="docutils literal notranslate"><span class="pre">bool</span></code>)</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">status</span></code> (<code class="docutils literal notranslate"><span class="pre">str</span></code>) - A status string indicating the current state of the Firewall.
This can be “waiting”, “succeeded”, or “failed”.</p></li>
</ul>
</dd></dl>

<dl class="py attribute">
<dt id="pulumi_digitalocean.Firewall.status">
<code class="sig-name descname">status</code><em class="property">: pulumi.Output[str]</em><em class="property"> = None</em><a class="headerlink" href="#pulumi_digitalocean.Firewall.status" title="Permalink to this definition">¶</a></dt>
<dd><p>A status string indicating the current state of the Firewall.
This can be “waiting”, “succeeded”, or “failed”.</p>
</dd></dl>

<dl class="py attribute">
<dt id="pulumi_digitalocean.Firewall.tags">
<code class="sig-name descname">tags</code><em class="property">: pulumi.Output[list]</em><em class="property"> = None</em><a class="headerlink" href="#pulumi_digitalocean.Firewall.tags" title="Permalink to this definition">¶</a></dt>
<dd><p>The names of the Tags assigned to the Firewall.</p>
</dd></dl>

<dl class="py method">
<dt id="pulumi_digitalocean.Firewall.get">
<em class="property">static </em><code class="sig-name descname">get</code><span class="sig-paren">(</span><em class="sig-param"><span class="n">resource_name</span></em>, <em class="sig-param"><span class="n">id</span></em>, <em class="sig-param"><span class="n">opts</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">created_at</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">droplet_ids</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">inbound_rules</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">name</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">outbound_rules</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">pending_changes</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">status</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">tags</span><span class="o">=</span><span class="default_value">None</span></em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_digitalocean.Firewall.get" title="Permalink to this definition">¶</a></dt>
<dd><p>Get an existing Firewall resource’s state with the given name, id, and optional extra
properties used to qualify the lookup.</p>
<dl class="field-list simple">
<dt class="field-odd">Parameters</dt>
<dd class="field-odd"><ul class="simple">
<li><p><strong>resource_name</strong> (<em>str</em>) – The unique name of the resulting resource.</p></li>
<li><p><strong>id</strong> (<em>str</em>) – The unique provider ID of the resource to lookup.</p></li>
<li><p><strong>opts</strong> (<a class="reference internal" href="../pulumi/#pulumi.ResourceOptions" title="pulumi.ResourceOptions"><em>pulumi.ResourceOptions</em></a>) – Options for the resource.</p></li>
<li><p><strong>created_at</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – A time value given in ISO8601 combined date and time format
that represents when the Firewall was created.</p></li>
<li><p><strong>droplet_ids</strong> (<em>pulumi.Input</em><em>[</em><em>list</em><em>]</em>) – The list of the IDs of the Droplets assigned
to the Firewall.</p></li>
<li><p><strong>inbound_rules</strong> (<em>pulumi.Input</em><em>[</em><em>list</em><em>]</em>) – The inbound access rule block for the Firewall.
The <code class="docutils literal notranslate"><span class="pre">inbound_rule</span></code> block is documented below.</p></li>
<li><p><strong>name</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – The Firewall name</p></li>
<li><p><strong>outbound_rules</strong> (<em>pulumi.Input</em><em>[</em><em>list</em><em>]</em>) – The outbound access rule block for the Firewall.
The <code class="docutils literal notranslate"><span class="pre">outbound_rule</span></code> block is documented below.</p></li>
<li><p><strong>pending_changes</strong> (<em>pulumi.Input</em><em>[</em><em>list</em><em>]</em>) – An list of object containing the fields, “droplet_id”,
“removing”, and “status”.  It is provided to detail exactly which Droplets
are having their security policies updated.  When empty, all changes
have been successfully applied.</p></li>
<li><p><strong>status</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – A status string indicating the current state of the Firewall.
This can be “waiting”, “succeeded”, or “failed”.</p></li>
<li><p><strong>tags</strong> (<em>pulumi.Input</em><em>[</em><em>list</em><em>]</em>) – The names of the Tags assigned to the Firewall.</p></li>
</ul>
</dd>
</dl>
<p>The <strong>inbound_rules</strong> object supports the following:</p>
<ul class="simple">
<li><p><code class="docutils literal notranslate"><span class="pre">portRange</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[str]</span></code>) - The ports on which traffic will be allowed
specified as a string containing a single port, a range (e.g. “8000-9000”),
or “1-65535” to open all ports for a protocol. Required for when protocol is
<code class="docutils literal notranslate"><span class="pre">tcp</span></code> or <code class="docutils literal notranslate"><span class="pre">udp</span></code>.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">protocol</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[str]</span></code>) - The type of traffic to be allowed.
This may be one of “tcp”, “udp”, or “icmp”.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">sourceAddresses</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[list]</span></code>) - An array of strings containing the IPv4
addresses, IPv6 addresses, IPv4 CIDRs, and/or IPv6 CIDRs from which the
inbound traffic will be accepted.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">sourceDropletIds</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[list]</span></code>) - An array containing the IDs of
the Droplets from which the inbound traffic will be accepted.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">sourceLoadBalancerUids</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[list]</span></code>) - An array containing the IDs
of the Load Balancers from which the inbound traffic will be accepted.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">sourceTags</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[list]</span></code>) - An array containing the names of Tags
corresponding to groups of Droplets from which the inbound traffic
will be accepted.</p></li>
</ul>
<p>The <strong>outbound_rules</strong> object supports the following:</p>
<ul class="simple">
<li><p><code class="docutils literal notranslate"><span class="pre">destinationAddresses</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[list]</span></code>) - An array of strings containing the IPv4
addresses, IPv6 addresses, IPv4 CIDRs, and/or IPv6 CIDRs to which the
outbound traffic will be allowed.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">destinationDropletIds</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[list]</span></code>) - An array containing the IDs of
the Droplets to which the outbound traffic will be allowed.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">destinationLoadBalancerUids</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[list]</span></code>) - An array containing the IDs
of the Load Balancers to which the outbound traffic will be allowed.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">destinationTags</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[list]</span></code>) - An array containing the names of Tags
corresponding to groups of Droplets to which the outbound traffic will
be allowed.
traffic.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">portRange</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[str]</span></code>) - The ports on which traffic will be allowed
specified as a string containing a single port, a range (e.g. “8000-9000”),
or “1-65535” to open all ports for a protocol. Required for when protocol is
<code class="docutils literal notranslate"><span class="pre">tcp</span></code> or <code class="docutils literal notranslate"><span class="pre">udp</span></code>.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">protocol</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[str]</span></code>) - The type of traffic to be allowed.
This may be one of “tcp”, “udp”, or “icmp”.</p></li>
</ul>
<p>The <strong>pending_changes</strong> object supports the following:</p>
<ul class="simple">
<li><p><code class="docutils literal notranslate"><span class="pre">droplet_id</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[float]</span></code>)</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">removing</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[bool]</span></code>)</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">status</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[str]</span></code>) - A status string indicating the current state of the Firewall.
This can be “waiting”, “succeeded”, or “failed”.</p></li>
</ul>
</dd></dl>

<dl class="py method">
<dt id="pulumi_digitalocean.Firewall.translate_output_property">
<code class="sig-name descname">translate_output_property</code><span class="sig-paren">(</span><em class="sig-param"><span class="n">prop</span></em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_digitalocean.Firewall.translate_output_property" title="Permalink to this definition">¶</a></dt>
<dd><p>Provides subclasses of Resource an opportunity to translate names of output properties
into a format of their choosing before writing those properties to the resource object.</p>
<dl class="field-list simple">
<dt class="field-odd">Parameters</dt>
<dd class="field-odd"><p><strong>prop</strong> (<em>str</em>) – A property name.</p>
</dd>
<dt class="field-even">Returns</dt>
<dd class="field-even"><p>A potentially transformed property name.</p>
</dd>
<dt class="field-odd">Return type</dt>
<dd class="field-odd"><p>str</p>
</dd>
</dl>
</dd></dl>

<dl class="py method">
<dt id="pulumi_digitalocean.Firewall.translate_input_property">
<code class="sig-name descname">translate_input_property</code><span class="sig-paren">(</span><em class="sig-param"><span class="n">prop</span></em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_digitalocean.Firewall.translate_input_property" title="Permalink to this definition">¶</a></dt>
<dd><p>Provides subclasses of Resource an opportunity to translate names of input properties into
a format of their choosing before sending those properties to the Pulumi engine.</p>
<dl class="field-list simple">
<dt class="field-odd">Parameters</dt>
<dd class="field-odd"><p><strong>prop</strong> (<em>str</em>) – A property name.</p>
</dd>
<dt class="field-even">Returns</dt>
<dd class="field-even"><p>A potentially transformed property name.</p>
</dd>
<dt class="field-odd">Return type</dt>
<dd class="field-odd"><p>str</p>
</dd>
</dl>
</dd></dl>

</dd></dl>

<dl class="py class">
<dt id="pulumi_digitalocean.FloatingIp">
<em class="property">class </em><code class="sig-prename descclassname">pulumi_digitalocean.</code><code class="sig-name descname">FloatingIp</code><span class="sig-paren">(</span><em class="sig-param"><span class="n">resource_name</span></em>, <em class="sig-param"><span class="n">opts</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">droplet_id</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">ip_address</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">region</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">__props__</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">__name__</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">__opts__</span><span class="o">=</span><span class="default_value">None</span></em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_digitalocean.FloatingIp" title="Permalink to this definition">¶</a></dt>
<dd><p>Provides a DigitalOcean Floating IP to represent a publicly-accessible static IP addresses that can be mapped to one of your Droplets.</p>
<blockquote>
<div><p><strong>NOTE:</strong> Floating IPs can be assigned to a Droplet either directly on the <code class="docutils literal notranslate"><span class="pre">.FloatingIp</span></code> resource by setting a <code class="docutils literal notranslate"><span class="pre">droplet_id</span></code> or using the <code class="docutils literal notranslate"><span class="pre">.FloatingIpAssignment</span></code> resource, but the two cannot be used together.</p>
</div></blockquote>
<div class="highlight-python notranslate"><div class="highlight"><pre><span></span><span class="kn">import</span> <span class="nn">pulumi</span>
<span class="kn">import</span> <span class="nn">pulumi_digitalocean</span> <span class="k">as</span> <span class="nn">digitalocean</span>

<span class="n">foobar_droplet</span> <span class="o">=</span> <span class="n">digitalocean</span><span class="o">.</span><span class="n">Droplet</span><span class="p">(</span><span class="s2">&quot;foobarDroplet&quot;</span><span class="p">,</span>
    <span class="n">size</span><span class="o">=</span><span class="s2">&quot;s-1vcpu-1gb&quot;</span><span class="p">,</span>
    <span class="n">image</span><span class="o">=</span><span class="s2">&quot;ubuntu-18-04-x64&quot;</span><span class="p">,</span>
    <span class="n">region</span><span class="o">=</span><span class="s2">&quot;sgp1&quot;</span><span class="p">,</span>
    <span class="n">ipv6</span><span class="o">=</span><span class="kc">True</span><span class="p">,</span>
    <span class="n">private_networking</span><span class="o">=</span><span class="kc">True</span><span class="p">)</span>
<span class="n">foobar_floating_ip</span> <span class="o">=</span> <span class="n">digitalocean</span><span class="o">.</span><span class="n">FloatingIp</span><span class="p">(</span><span class="s2">&quot;foobarFloatingIp&quot;</span><span class="p">,</span>
    <span class="n">droplet_id</span><span class="o">=</span><span class="n">foobar_droplet</span><span class="o">.</span><span class="n">id</span><span class="p">,</span>
    <span class="n">region</span><span class="o">=</span><span class="n">foobar_droplet</span><span class="o">.</span><span class="n">region</span><span class="p">)</span>
</pre></div>
</div>
<dl class="field-list simple">
<dt class="field-odd">Parameters</dt>
<dd class="field-odd"><ul class="simple">
<li><p><strong>resource_name</strong> (<em>str</em>) – The name of the resource.</p></li>
<li><p><strong>opts</strong> (<a class="reference internal" href="../pulumi/#pulumi.ResourceOptions" title="pulumi.ResourceOptions"><em>pulumi.ResourceOptions</em></a>) – Options for the resource.</p></li>
<li><p><strong>droplet_id</strong> (<em>pulumi.Input</em><em>[</em><em>float</em><em>]</em>) – The ID of Droplet that the Floating IP will be assigned to.</p></li>
<li><p><strong>ip_address</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – The IP Address of the resource</p></li>
<li><p><strong>region</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – The region that the Floating IP is reserved to.</p></li>
</ul>
</dd>
</dl>
<dl class="py attribute">
<dt id="pulumi_digitalocean.FloatingIp.droplet_id">
<code class="sig-name descname">droplet_id</code><em class="property">: pulumi.Output[float]</em><em class="property"> = None</em><a class="headerlink" href="#pulumi_digitalocean.FloatingIp.droplet_id" title="Permalink to this definition">¶</a></dt>
<dd><p>The ID of Droplet that the Floating IP will be assigned to.</p>
</dd></dl>

<dl class="py attribute">
<dt id="pulumi_digitalocean.FloatingIp.ip_address">
<code class="sig-name descname">ip_address</code><em class="property">: pulumi.Output[str]</em><em class="property"> = None</em><a class="headerlink" href="#pulumi_digitalocean.FloatingIp.ip_address" title="Permalink to this definition">¶</a></dt>
<dd><p>The IP Address of the resource</p>
</dd></dl>

<dl class="py attribute">
<dt id="pulumi_digitalocean.FloatingIp.region">
<code class="sig-name descname">region</code><em class="property">: pulumi.Output[str]</em><em class="property"> = None</em><a class="headerlink" href="#pulumi_digitalocean.FloatingIp.region" title="Permalink to this definition">¶</a></dt>
<dd><p>The region that the Floating IP is reserved to.</p>
</dd></dl>

<dl class="py attribute">
<dt id="pulumi_digitalocean.FloatingIp.urn">
<code class="sig-name descname">urn</code><em class="property">: pulumi.Output[str]</em><em class="property"> = None</em><a class="headerlink" href="#pulumi_digitalocean.FloatingIp.urn" title="Permalink to this definition">¶</a></dt>
<dd><p>The uniform resource name of the floating ip</p>
</dd></dl>

<dl class="py method">
<dt id="pulumi_digitalocean.FloatingIp.get">
<em class="property">static </em><code class="sig-name descname">get</code><span class="sig-paren">(</span><em class="sig-param"><span class="n">resource_name</span></em>, <em class="sig-param"><span class="n">id</span></em>, <em class="sig-param"><span class="n">opts</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">droplet_id</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">ip_address</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">region</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">urn</span><span class="o">=</span><span class="default_value">None</span></em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_digitalocean.FloatingIp.get" title="Permalink to this definition">¶</a></dt>
<dd><p>Get an existing FloatingIp resource’s state with the given name, id, and optional extra
properties used to qualify the lookup.</p>
<dl class="field-list simple">
<dt class="field-odd">Parameters</dt>
<dd class="field-odd"><ul class="simple">
<li><p><strong>resource_name</strong> (<em>str</em>) – The unique name of the resulting resource.</p></li>
<li><p><strong>id</strong> (<em>str</em>) – The unique provider ID of the resource to lookup.</p></li>
<li><p><strong>opts</strong> (<a class="reference internal" href="../pulumi/#pulumi.ResourceOptions" title="pulumi.ResourceOptions"><em>pulumi.ResourceOptions</em></a>) – Options for the resource.</p></li>
<li><p><strong>droplet_id</strong> (<em>pulumi.Input</em><em>[</em><em>float</em><em>]</em>) – The ID of Droplet that the Floating IP will be assigned to.</p></li>
<li><p><strong>ip_address</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – The IP Address of the resource</p></li>
<li><p><strong>region</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – The region that the Floating IP is reserved to.</p></li>
<li><p><strong>urn</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – The uniform resource name of the floating ip</p></li>
</ul>
</dd>
</dl>
</dd></dl>

<dl class="py method">
<dt id="pulumi_digitalocean.FloatingIp.translate_output_property">
<code class="sig-name descname">translate_output_property</code><span class="sig-paren">(</span><em class="sig-param"><span class="n">prop</span></em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_digitalocean.FloatingIp.translate_output_property" title="Permalink to this definition">¶</a></dt>
<dd><p>Provides subclasses of Resource an opportunity to translate names of output properties
into a format of their choosing before writing those properties to the resource object.</p>
<dl class="field-list simple">
<dt class="field-odd">Parameters</dt>
<dd class="field-odd"><p><strong>prop</strong> (<em>str</em>) – A property name.</p>
</dd>
<dt class="field-even">Returns</dt>
<dd class="field-even"><p>A potentially transformed property name.</p>
</dd>
<dt class="field-odd">Return type</dt>
<dd class="field-odd"><p>str</p>
</dd>
</dl>
</dd></dl>

<dl class="py method">
<dt id="pulumi_digitalocean.FloatingIp.translate_input_property">
<code class="sig-name descname">translate_input_property</code><span class="sig-paren">(</span><em class="sig-param"><span class="n">prop</span></em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_digitalocean.FloatingIp.translate_input_property" title="Permalink to this definition">¶</a></dt>
<dd><p>Provides subclasses of Resource an opportunity to translate names of input properties into
a format of their choosing before sending those properties to the Pulumi engine.</p>
<dl class="field-list simple">
<dt class="field-odd">Parameters</dt>
<dd class="field-odd"><p><strong>prop</strong> (<em>str</em>) – A property name.</p>
</dd>
<dt class="field-even">Returns</dt>
<dd class="field-even"><p>A potentially transformed property name.</p>
</dd>
<dt class="field-odd">Return type</dt>
<dd class="field-odd"><p>str</p>
</dd>
</dl>
</dd></dl>

</dd></dl>

<dl class="py class">
<dt id="pulumi_digitalocean.FloatingIpAssignment">
<em class="property">class </em><code class="sig-prename descclassname">pulumi_digitalocean.</code><code class="sig-name descname">FloatingIpAssignment</code><span class="sig-paren">(</span><em class="sig-param"><span class="n">resource_name</span></em>, <em class="sig-param"><span class="n">opts</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">droplet_id</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">ip_address</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">__props__</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">__name__</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">__opts__</span><span class="o">=</span><span class="default_value">None</span></em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_digitalocean.FloatingIpAssignment" title="Permalink to this definition">¶</a></dt>
<dd><p>Provides a resource for assigning an existing DigitalOcean Floating IP to a Droplet. This
makes it easy to provision floating IP addresses that are not tied to the lifecycle of your
Droplet.</p>
<div class="highlight-python notranslate"><div class="highlight"><pre><span></span><span class="kn">import</span> <span class="nn">pulumi</span>
<span class="kn">import</span> <span class="nn">pulumi_digitalocean</span> <span class="k">as</span> <span class="nn">digitalocean</span>

<span class="n">foobar_floating_ip</span> <span class="o">=</span> <span class="n">digitalocean</span><span class="o">.</span><span class="n">FloatingIp</span><span class="p">(</span><span class="s2">&quot;foobarFloatingIp&quot;</span><span class="p">,</span> <span class="n">region</span><span class="o">=</span><span class="s2">&quot;sgp1&quot;</span><span class="p">)</span>
<span class="n">foobar_droplet</span> <span class="o">=</span> <span class="n">digitalocean</span><span class="o">.</span><span class="n">Droplet</span><span class="p">(</span><span class="s2">&quot;foobarDroplet&quot;</span><span class="p">,</span>
    <span class="n">size</span><span class="o">=</span><span class="s2">&quot;s-1vcpu-1gb&quot;</span><span class="p">,</span>
    <span class="n">image</span><span class="o">=</span><span class="s2">&quot;ubuntu-18-04-x64&quot;</span><span class="p">,</span>
    <span class="n">region</span><span class="o">=</span><span class="s2">&quot;sgp1&quot;</span><span class="p">,</span>
    <span class="n">ipv6</span><span class="o">=</span><span class="kc">True</span><span class="p">,</span>
    <span class="n">private_networking</span><span class="o">=</span><span class="kc">True</span><span class="p">)</span>
<span class="n">foobar_floating_ip_assignment</span> <span class="o">=</span> <span class="n">digitalocean</span><span class="o">.</span><span class="n">FloatingIpAssignment</span><span class="p">(</span><span class="s2">&quot;foobarFloatingIpAssignment&quot;</span><span class="p">,</span>
    <span class="n">ip_address</span><span class="o">=</span><span class="n">foobar_floating_ip</span><span class="o">.</span><span class="n">ip_address</span><span class="p">,</span>
    <span class="n">droplet_id</span><span class="o">=</span><span class="n">foobar_droplet</span><span class="o">.</span><span class="n">id</span><span class="p">)</span>
</pre></div>
</div>
<dl class="field-list simple">
<dt class="field-odd">Parameters</dt>
<dd class="field-odd"><ul class="simple">
<li><p><strong>resource_name</strong> (<em>str</em>) – The name of the resource.</p></li>
<li><p><strong>opts</strong> (<a class="reference internal" href="../pulumi/#pulumi.ResourceOptions" title="pulumi.ResourceOptions"><em>pulumi.ResourceOptions</em></a>) – Options for the resource.</p></li>
<li><p><strong>droplet_id</strong> (<em>pulumi.Input</em><em>[</em><em>float</em><em>]</em>) – The ID of Droplet that the Floating IP will be assigned to.</p></li>
<li><p><strong>ip_address</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – The Floating IP to assign to the Droplet.</p></li>
</ul>
</dd>
</dl>
<dl class="py attribute">
<dt id="pulumi_digitalocean.FloatingIpAssignment.droplet_id">
<code class="sig-name descname">droplet_id</code><em class="property">: pulumi.Output[float]</em><em class="property"> = None</em><a class="headerlink" href="#pulumi_digitalocean.FloatingIpAssignment.droplet_id" title="Permalink to this definition">¶</a></dt>
<dd><p>The ID of Droplet that the Floating IP will be assigned to.</p>
</dd></dl>

<dl class="py attribute">
<dt id="pulumi_digitalocean.FloatingIpAssignment.ip_address">
<code class="sig-name descname">ip_address</code><em class="property">: pulumi.Output[str]</em><em class="property"> = None</em><a class="headerlink" href="#pulumi_digitalocean.FloatingIpAssignment.ip_address" title="Permalink to this definition">¶</a></dt>
<dd><p>The Floating IP to assign to the Droplet.</p>
</dd></dl>

<dl class="py method">
<dt id="pulumi_digitalocean.FloatingIpAssignment.get">
<em class="property">static </em><code class="sig-name descname">get</code><span class="sig-paren">(</span><em class="sig-param"><span class="n">resource_name</span></em>, <em class="sig-param"><span class="n">id</span></em>, <em class="sig-param"><span class="n">opts</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">droplet_id</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">ip_address</span><span class="o">=</span><span class="default_value">None</span></em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_digitalocean.FloatingIpAssignment.get" title="Permalink to this definition">¶</a></dt>
<dd><p>Get an existing FloatingIpAssignment resource’s state with the given name, id, and optional extra
properties used to qualify the lookup.</p>
<dl class="field-list simple">
<dt class="field-odd">Parameters</dt>
<dd class="field-odd"><ul class="simple">
<li><p><strong>resource_name</strong> (<em>str</em>) – The unique name of the resulting resource.</p></li>
<li><p><strong>id</strong> (<em>str</em>) – The unique provider ID of the resource to lookup.</p></li>
<li><p><strong>opts</strong> (<a class="reference internal" href="../pulumi/#pulumi.ResourceOptions" title="pulumi.ResourceOptions"><em>pulumi.ResourceOptions</em></a>) – Options for the resource.</p></li>
<li><p><strong>droplet_id</strong> (<em>pulumi.Input</em><em>[</em><em>float</em><em>]</em>) – The ID of Droplet that the Floating IP will be assigned to.</p></li>
<li><p><strong>ip_address</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – The Floating IP to assign to the Droplet.</p></li>
</ul>
</dd>
</dl>
</dd></dl>

<dl class="py method">
<dt id="pulumi_digitalocean.FloatingIpAssignment.translate_output_property">
<code class="sig-name descname">translate_output_property</code><span class="sig-paren">(</span><em class="sig-param"><span class="n">prop</span></em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_digitalocean.FloatingIpAssignment.translate_output_property" title="Permalink to this definition">¶</a></dt>
<dd><p>Provides subclasses of Resource an opportunity to translate names of output properties
into a format of their choosing before writing those properties to the resource object.</p>
<dl class="field-list simple">
<dt class="field-odd">Parameters</dt>
<dd class="field-odd"><p><strong>prop</strong> (<em>str</em>) – A property name.</p>
</dd>
<dt class="field-even">Returns</dt>
<dd class="field-even"><p>A potentially transformed property name.</p>
</dd>
<dt class="field-odd">Return type</dt>
<dd class="field-odd"><p>str</p>
</dd>
</dl>
</dd></dl>

<dl class="py method">
<dt id="pulumi_digitalocean.FloatingIpAssignment.translate_input_property">
<code class="sig-name descname">translate_input_property</code><span class="sig-paren">(</span><em class="sig-param"><span class="n">prop</span></em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_digitalocean.FloatingIpAssignment.translate_input_property" title="Permalink to this definition">¶</a></dt>
<dd><p>Provides subclasses of Resource an opportunity to translate names of input properties into
a format of their choosing before sending those properties to the Pulumi engine.</p>
<dl class="field-list simple">
<dt class="field-odd">Parameters</dt>
<dd class="field-odd"><p><strong>prop</strong> (<em>str</em>) – A property name.</p>
</dd>
<dt class="field-even">Returns</dt>
<dd class="field-even"><p>A potentially transformed property name.</p>
</dd>
<dt class="field-odd">Return type</dt>
<dd class="field-odd"><p>str</p>
</dd>
</dl>
</dd></dl>

</dd></dl>

<dl class="py class">
<dt id="pulumi_digitalocean.GetAccountResult">
<em class="property">class </em><code class="sig-prename descclassname">pulumi_digitalocean.</code><code class="sig-name descname">GetAccountResult</code><span class="sig-paren">(</span><em class="sig-param"><span class="n">droplet_limit</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">email</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">email_verified</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">floating_ip_limit</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">id</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">status</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">status_message</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">uuid</span><span class="o">=</span><span class="default_value">None</span></em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_digitalocean.GetAccountResult" title="Permalink to this definition">¶</a></dt>
<dd><p>A collection of values returned by getAccount.</p>
<dl class="py attribute">
<dt id="pulumi_digitalocean.GetAccountResult.id">
<code class="sig-name descname">id</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_digitalocean.GetAccountResult.id" title="Permalink to this definition">¶</a></dt>
<dd><p>The provider-assigned unique ID for this managed resource.</p>
</dd></dl>

</dd></dl>

<dl class="py class">
<dt id="pulumi_digitalocean.GetCertificateResult">
<em class="property">class </em><code class="sig-prename descclassname">pulumi_digitalocean.</code><code class="sig-name descname">GetCertificateResult</code><span class="sig-paren">(</span><em class="sig-param"><span class="n">domains</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">id</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">name</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">not_after</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">sha1_fingerprint</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">state</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">type</span><span class="o">=</span><span class="default_value">None</span></em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_digitalocean.GetCertificateResult" title="Permalink to this definition">¶</a></dt>
<dd><p>A collection of values returned by getCertificate.</p>
<dl class="py attribute">
<dt id="pulumi_digitalocean.GetCertificateResult.id">
<code class="sig-name descname">id</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_digitalocean.GetCertificateResult.id" title="Permalink to this definition">¶</a></dt>
<dd><p>The provider-assigned unique ID for this managed resource.</p>
</dd></dl>

</dd></dl>

<dl class="py class">
<dt id="pulumi_digitalocean.GetDatabaseClusterResult">
<em class="property">class </em><code class="sig-prename descclassname">pulumi_digitalocean.</code><code class="sig-name descname">GetDatabaseClusterResult</code><span class="sig-paren">(</span><em class="sig-param"><span class="n">database</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">engine</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">host</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">id</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">maintenance_windows</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">name</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">node_count</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">password</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">port</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">private_host</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">private_network_uuid</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">private_uri</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">region</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">size</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">tags</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">uri</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">urn</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">user</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">version</span><span class="o">=</span><span class="default_value">None</span></em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_digitalocean.GetDatabaseClusterResult" title="Permalink to this definition">¶</a></dt>
<dd><p>A collection of values returned by getDatabaseCluster.</p>
<dl class="py attribute">
<dt id="pulumi_digitalocean.GetDatabaseClusterResult.database">
<code class="sig-name descname">database</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_digitalocean.GetDatabaseClusterResult.database" title="Permalink to this definition">¶</a></dt>
<dd><p>Name of the cluster’s default database.</p>
</dd></dl>

<dl class="py attribute">
<dt id="pulumi_digitalocean.GetDatabaseClusterResult.engine">
<code class="sig-name descname">engine</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_digitalocean.GetDatabaseClusterResult.engine" title="Permalink to this definition">¶</a></dt>
<dd><p>Database engine used by the cluster (ex. <code class="docutils literal notranslate"><span class="pre">pg</span></code> for PostreSQL).</p>
</dd></dl>

<dl class="py attribute">
<dt id="pulumi_digitalocean.GetDatabaseClusterResult.host">
<code class="sig-name descname">host</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_digitalocean.GetDatabaseClusterResult.host" title="Permalink to this definition">¶</a></dt>
<dd><p>Database cluster’s hostname.</p>
</dd></dl>

<dl class="py attribute">
<dt id="pulumi_digitalocean.GetDatabaseClusterResult.id">
<code class="sig-name descname">id</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_digitalocean.GetDatabaseClusterResult.id" title="Permalink to this definition">¶</a></dt>
<dd><p>The provider-assigned unique ID for this managed resource.</p>
</dd></dl>

<dl class="py attribute">
<dt id="pulumi_digitalocean.GetDatabaseClusterResult.maintenance_windows">
<code class="sig-name descname">maintenance_windows</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_digitalocean.GetDatabaseClusterResult.maintenance_windows" title="Permalink to this definition">¶</a></dt>
<dd><p>Defines when the automatic maintenance should be performed for the database cluster.</p>
</dd></dl>

<dl class="py attribute">
<dt id="pulumi_digitalocean.GetDatabaseClusterResult.node_count">
<code class="sig-name descname">node_count</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_digitalocean.GetDatabaseClusterResult.node_count" title="Permalink to this definition">¶</a></dt>
<dd><p>Number of nodes that will be included in the cluster.</p>
</dd></dl>

<dl class="py attribute">
<dt id="pulumi_digitalocean.GetDatabaseClusterResult.password">
<code class="sig-name descname">password</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_digitalocean.GetDatabaseClusterResult.password" title="Permalink to this definition">¶</a></dt>
<dd><p>Password for the cluster’s default user.</p>
</dd></dl>

<dl class="py attribute">
<dt id="pulumi_digitalocean.GetDatabaseClusterResult.port">
<code class="sig-name descname">port</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_digitalocean.GetDatabaseClusterResult.port" title="Permalink to this definition">¶</a></dt>
<dd><p>Network port that the database cluster is listening on.</p>
</dd></dl>

<dl class="py attribute">
<dt id="pulumi_digitalocean.GetDatabaseClusterResult.private_host">
<code class="sig-name descname">private_host</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_digitalocean.GetDatabaseClusterResult.private_host" title="Permalink to this definition">¶</a></dt>
<dd><p>Same as <code class="docutils literal notranslate"><span class="pre">host</span></code>, but only accessible from resources within the account and in the same region.</p>
</dd></dl>

<dl class="py attribute">
<dt id="pulumi_digitalocean.GetDatabaseClusterResult.private_network_uuid">
<code class="sig-name descname">private_network_uuid</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_digitalocean.GetDatabaseClusterResult.private_network_uuid" title="Permalink to this definition">¶</a></dt>
<dd><p>The ID of the VPC where the database cluster is located.</p>
</dd></dl>

<dl class="py attribute">
<dt id="pulumi_digitalocean.GetDatabaseClusterResult.private_uri">
<code class="sig-name descname">private_uri</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_digitalocean.GetDatabaseClusterResult.private_uri" title="Permalink to this definition">¶</a></dt>
<dd><p>Same as <code class="docutils literal notranslate"><span class="pre">uri</span></code>, but only accessible from resources within the account and in the same region.</p>
</dd></dl>

<dl class="py attribute">
<dt id="pulumi_digitalocean.GetDatabaseClusterResult.region">
<code class="sig-name descname">region</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_digitalocean.GetDatabaseClusterResult.region" title="Permalink to this definition">¶</a></dt>
<dd><p>DigitalOcean region where the cluster will reside.</p>
</dd></dl>

<dl class="py attribute">
<dt id="pulumi_digitalocean.GetDatabaseClusterResult.size">
<code class="sig-name descname">size</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_digitalocean.GetDatabaseClusterResult.size" title="Permalink to this definition">¶</a></dt>
<dd><p>Database droplet size associated with the cluster (ex. <code class="docutils literal notranslate"><span class="pre">db-s-1vcpu-1gb</span></code>).</p>
</dd></dl>

<dl class="py attribute">
<dt id="pulumi_digitalocean.GetDatabaseClusterResult.uri">
<code class="sig-name descname">uri</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_digitalocean.GetDatabaseClusterResult.uri" title="Permalink to this definition">¶</a></dt>
<dd><p>The full URI for connecting to the database cluster.</p>
</dd></dl>

<dl class="py attribute">
<dt id="pulumi_digitalocean.GetDatabaseClusterResult.urn">
<code class="sig-name descname">urn</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_digitalocean.GetDatabaseClusterResult.urn" title="Permalink to this definition">¶</a></dt>
<dd><p>The uniform resource name of the database cluster.</p>
</dd></dl>

<dl class="py attribute">
<dt id="pulumi_digitalocean.GetDatabaseClusterResult.user">
<code class="sig-name descname">user</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_digitalocean.GetDatabaseClusterResult.user" title="Permalink to this definition">¶</a></dt>
<dd><p>Username for the cluster’s default user.</p>
</dd></dl>

<dl class="py attribute">
<dt id="pulumi_digitalocean.GetDatabaseClusterResult.version">
<code class="sig-name descname">version</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_digitalocean.GetDatabaseClusterResult.version" title="Permalink to this definition">¶</a></dt>
<dd><p>Engine version used by the cluster (ex. <code class="docutils literal notranslate"><span class="pre">11</span></code> for PostgreSQL 11).</p>
</dd></dl>

</dd></dl>

<dl class="py class">
<dt id="pulumi_digitalocean.GetDomainResult">
<em class="property">class </em><code class="sig-prename descclassname">pulumi_digitalocean.</code><code class="sig-name descname">GetDomainResult</code><span class="sig-paren">(</span><em class="sig-param"><span class="n">id</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">name</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">ttl</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">urn</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">zone_file</span><span class="o">=</span><span class="default_value">None</span></em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_digitalocean.GetDomainResult" title="Permalink to this definition">¶</a></dt>
<dd><p>A collection of values returned by getDomain.</p>
<dl class="py attribute">
<dt id="pulumi_digitalocean.GetDomainResult.id">
<code class="sig-name descname">id</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_digitalocean.GetDomainResult.id" title="Permalink to this definition">¶</a></dt>
<dd><p>The provider-assigned unique ID for this managed resource.</p>
</dd></dl>

<dl class="py attribute">
<dt id="pulumi_digitalocean.GetDomainResult.urn">
<code class="sig-name descname">urn</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_digitalocean.GetDomainResult.urn" title="Permalink to this definition">¶</a></dt>
<dd><p>The uniform resource name of the domain</p>
<ul class="simple">
<li><p><code class="docutils literal notranslate"><span class="pre">zone_file</span></code>: The zone file of the domain.</p></li>
</ul>
</dd></dl>

</dd></dl>

<dl class="py class">
<dt id="pulumi_digitalocean.GetDropletResult">
<em class="property">class </em><code class="sig-prename descclassname">pulumi_digitalocean.</code><code class="sig-name descname">GetDropletResult</code><span class="sig-paren">(</span><em class="sig-param"><span class="n">backups</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">created_at</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">disk</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">id</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">image</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">ipv4_address</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">ipv4_address_private</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">ipv6</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">ipv6_address</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">ipv6_address_private</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">locked</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">memory</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">monitoring</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">name</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">price_hourly</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">price_monthly</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">private_networking</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">region</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">size</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">status</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">tag</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">tags</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">urn</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">vcpus</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">volume_ids</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">vpc_uuid</span><span class="o">=</span><span class="default_value">None</span></em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_digitalocean.GetDropletResult" title="Permalink to this definition">¶</a></dt>
<dd><p>A collection of values returned by getDroplet.</p>
<dl class="py attribute">
<dt id="pulumi_digitalocean.GetDropletResult.backups">
<code class="sig-name descname">backups</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_digitalocean.GetDropletResult.backups" title="Permalink to this definition">¶</a></dt>
<dd><p>Whether backups are enabled.</p>
</dd></dl>

<dl class="py attribute">
<dt id="pulumi_digitalocean.GetDropletResult.disk">
<code class="sig-name descname">disk</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_digitalocean.GetDropletResult.disk" title="Permalink to this definition">¶</a></dt>
<dd><p>The size of the Droplets disk in GB.</p>
</dd></dl>

<dl class="py attribute">
<dt id="pulumi_digitalocean.GetDropletResult.image">
<code class="sig-name descname">image</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_digitalocean.GetDropletResult.image" title="Permalink to this definition">¶</a></dt>
<dd><p>The Droplet image ID or slug.</p>
</dd></dl>

<dl class="py attribute">
<dt id="pulumi_digitalocean.GetDropletResult.ipv4_address">
<code class="sig-name descname">ipv4_address</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_digitalocean.GetDropletResult.ipv4_address" title="Permalink to this definition">¶</a></dt>
<dd><p>The Droplets public IPv4 address</p>
</dd></dl>

<dl class="py attribute">
<dt id="pulumi_digitalocean.GetDropletResult.ipv4_address_private">
<code class="sig-name descname">ipv4_address_private</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_digitalocean.GetDropletResult.ipv4_address_private" title="Permalink to this definition">¶</a></dt>
<dd><p>The Droplets private IPv4 address</p>
</dd></dl>

<dl class="py attribute">
<dt id="pulumi_digitalocean.GetDropletResult.ipv6">
<code class="sig-name descname">ipv6</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_digitalocean.GetDropletResult.ipv6" title="Permalink to this definition">¶</a></dt>
<dd><p>Whether IPv6 is enabled.</p>
</dd></dl>

<dl class="py attribute">
<dt id="pulumi_digitalocean.GetDropletResult.ipv6_address">
<code class="sig-name descname">ipv6_address</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_digitalocean.GetDropletResult.ipv6_address" title="Permalink to this definition">¶</a></dt>
<dd><p>The Droplets public IPv6 address</p>
</dd></dl>

<dl class="py attribute">
<dt id="pulumi_digitalocean.GetDropletResult.ipv6_address_private">
<code class="sig-name descname">ipv6_address_private</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_digitalocean.GetDropletResult.ipv6_address_private" title="Permalink to this definition">¶</a></dt>
<dd><p>The Droplets private IPv6 address</p>
</dd></dl>

<dl class="py attribute">
<dt id="pulumi_digitalocean.GetDropletResult.locked">
<code class="sig-name descname">locked</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_digitalocean.GetDropletResult.locked" title="Permalink to this definition">¶</a></dt>
<dd><p>Whether the Droplet is locked.</p>
</dd></dl>

<dl class="py attribute">
<dt id="pulumi_digitalocean.GetDropletResult.memory">
<code class="sig-name descname">memory</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_digitalocean.GetDropletResult.memory" title="Permalink to this definition">¶</a></dt>
<dd><p>The amount of the Droplets memory in MB.</p>
</dd></dl>

<dl class="py attribute">
<dt id="pulumi_digitalocean.GetDropletResult.monitoring">
<code class="sig-name descname">monitoring</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_digitalocean.GetDropletResult.monitoring" title="Permalink to this definition">¶</a></dt>
<dd><p>Whether monitoring agent is installed.</p>
</dd></dl>

<dl class="py attribute">
<dt id="pulumi_digitalocean.GetDropletResult.price_hourly">
<code class="sig-name descname">price_hourly</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_digitalocean.GetDropletResult.price_hourly" title="Permalink to this definition">¶</a></dt>
<dd><p>Droplet hourly price.</p>
</dd></dl>

<dl class="py attribute">
<dt id="pulumi_digitalocean.GetDropletResult.price_monthly">
<code class="sig-name descname">price_monthly</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_digitalocean.GetDropletResult.price_monthly" title="Permalink to this definition">¶</a></dt>
<dd><p>Droplet monthly price.</p>
</dd></dl>

<dl class="py attribute">
<dt id="pulumi_digitalocean.GetDropletResult.private_networking">
<code class="sig-name descname">private_networking</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_digitalocean.GetDropletResult.private_networking" title="Permalink to this definition">¶</a></dt>
<dd><p>Whether private networks are enabled.</p>
</dd></dl>

<dl class="py attribute">
<dt id="pulumi_digitalocean.GetDropletResult.region">
<code class="sig-name descname">region</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_digitalocean.GetDropletResult.region" title="Permalink to this definition">¶</a></dt>
<dd><p>The region the Droplet is running in.</p>
</dd></dl>

<dl class="py attribute">
<dt id="pulumi_digitalocean.GetDropletResult.size">
<code class="sig-name descname">size</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_digitalocean.GetDropletResult.size" title="Permalink to this definition">¶</a></dt>
<dd><p>The unique slug that indentifies the type of Droplet.</p>
</dd></dl>

<dl class="py attribute">
<dt id="pulumi_digitalocean.GetDropletResult.status">
<code class="sig-name descname">status</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_digitalocean.GetDropletResult.status" title="Permalink to this definition">¶</a></dt>
<dd><p>The status of the Droplet.</p>
</dd></dl>

<dl class="py attribute">
<dt id="pulumi_digitalocean.GetDropletResult.tags">
<code class="sig-name descname">tags</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_digitalocean.GetDropletResult.tags" title="Permalink to this definition">¶</a></dt>
<dd><p>A list of the tags associated to the Droplet.</p>
</dd></dl>

<dl class="py attribute">
<dt id="pulumi_digitalocean.GetDropletResult.urn">
<code class="sig-name descname">urn</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_digitalocean.GetDropletResult.urn" title="Permalink to this definition">¶</a></dt>
<dd><p>The uniform resource name of the Droplet</p>
</dd></dl>

<dl class="py attribute">
<dt id="pulumi_digitalocean.GetDropletResult.vcpus">
<code class="sig-name descname">vcpus</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_digitalocean.GetDropletResult.vcpus" title="Permalink to this definition">¶</a></dt>
<dd><p>The number of the Droplets virtual CPUs.</p>
</dd></dl>

<dl class="py attribute">
<dt id="pulumi_digitalocean.GetDropletResult.volume_ids">
<code class="sig-name descname">volume_ids</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_digitalocean.GetDropletResult.volume_ids" title="Permalink to this definition">¶</a></dt>
<dd><p>List of the IDs of each volumes attached to the Droplet.</p>
</dd></dl>

<dl class="py attribute">
<dt id="pulumi_digitalocean.GetDropletResult.vpc_uuid">
<code class="sig-name descname">vpc_uuid</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_digitalocean.GetDropletResult.vpc_uuid" title="Permalink to this definition">¶</a></dt>
<dd><p>The ID of the VPC where the Droplet is located.</p>
</dd></dl>

</dd></dl>

<dl class="py class">
<dt id="pulumi_digitalocean.GetDropletSnapshotResult">
<em class="property">class </em><code class="sig-prename descclassname">pulumi_digitalocean.</code><code class="sig-name descname">GetDropletSnapshotResult</code><span class="sig-paren">(</span><em class="sig-param"><span class="n">created_at</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">droplet_id</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">id</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">min_disk_size</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">most_recent</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">name</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">name_regex</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">region</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">regions</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">size</span><span class="o">=</span><span class="default_value">None</span></em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_digitalocean.GetDropletSnapshotResult" title="Permalink to this definition">¶</a></dt>
<dd><p>A collection of values returned by getDropletSnapshot.</p>
<dl class="py attribute">
<dt id="pulumi_digitalocean.GetDropletSnapshotResult.created_at">
<code class="sig-name descname">created_at</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_digitalocean.GetDropletSnapshotResult.created_at" title="Permalink to this definition">¶</a></dt>
<dd><p>The date and time the Droplet snapshot was created.</p>
</dd></dl>

<dl class="py attribute">
<dt id="pulumi_digitalocean.GetDropletSnapshotResult.droplet_id">
<code class="sig-name descname">droplet_id</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_digitalocean.GetDropletSnapshotResult.droplet_id" title="Permalink to this definition">¶</a></dt>
<dd><p>The ID of the Droplet from which the Droplet snapshot originated.</p>
</dd></dl>

<dl class="py attribute">
<dt id="pulumi_digitalocean.GetDropletSnapshotResult.id">
<code class="sig-name descname">id</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_digitalocean.GetDropletSnapshotResult.id" title="Permalink to this definition">¶</a></dt>
<dd><p>The provider-assigned unique ID for this managed resource.</p>
</dd></dl>

<dl class="py attribute">
<dt id="pulumi_digitalocean.GetDropletSnapshotResult.min_disk_size">
<code class="sig-name descname">min_disk_size</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_digitalocean.GetDropletSnapshotResult.min_disk_size" title="Permalink to this definition">¶</a></dt>
<dd><p>The minimum size in gigabytes required for a Droplet to be created based on this Droplet snapshot.</p>
</dd></dl>

<dl class="py attribute">
<dt id="pulumi_digitalocean.GetDropletSnapshotResult.regions">
<code class="sig-name descname">regions</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_digitalocean.GetDropletSnapshotResult.regions" title="Permalink to this definition">¶</a></dt>
<dd><p>A list of DigitalOcean region “slugs” indicating where the Droplet snapshot is available.</p>
</dd></dl>

<dl class="py attribute">
<dt id="pulumi_digitalocean.GetDropletSnapshotResult.size">
<code class="sig-name descname">size</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_digitalocean.GetDropletSnapshotResult.size" title="Permalink to this definition">¶</a></dt>
<dd><p>The billable size of the Droplet snapshot in gigabytes.</p>
</dd></dl>

</dd></dl>

<dl class="py class">
<dt id="pulumi_digitalocean.GetDropletsResult">
<em class="property">class </em><code class="sig-prename descclassname">pulumi_digitalocean.</code><code class="sig-name descname">GetDropletsResult</code><span class="sig-paren">(</span><em class="sig-param"><span class="n">droplets</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">filters</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">id</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">sorts</span><span class="o">=</span><span class="default_value">None</span></em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_digitalocean.GetDropletsResult" title="Permalink to this definition">¶</a></dt>
<dd><p>A collection of values returned by getDroplets.</p>
<dl class="py attribute">
<dt id="pulumi_digitalocean.GetDropletsResult.droplets">
<code class="sig-name descname">droplets</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_digitalocean.GetDropletsResult.droplets" title="Permalink to this definition">¶</a></dt>
<dd><p>A list of Droplets satisfying any <code class="docutils literal notranslate"><span class="pre">filter</span></code> and <code class="docutils literal notranslate"><span class="pre">sort</span></code> criteria. Each Droplet has the following attributes:</p>
</dd></dl>

<dl class="py attribute">
<dt id="pulumi_digitalocean.GetDropletsResult.id">
<code class="sig-name descname">id</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_digitalocean.GetDropletsResult.id" title="Permalink to this definition">¶</a></dt>
<dd><p>The provider-assigned unique ID for this managed resource.</p>
</dd></dl>

</dd></dl>

<dl class="py class">
<dt id="pulumi_digitalocean.GetFloatingIpResult">
<em class="property">class </em><code class="sig-prename descclassname">pulumi_digitalocean.</code><code class="sig-name descname">GetFloatingIpResult</code><span class="sig-paren">(</span><em class="sig-param"><span class="n">droplet_id</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">id</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">ip_address</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">region</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">urn</span><span class="o">=</span><span class="default_value">None</span></em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_digitalocean.GetFloatingIpResult" title="Permalink to this definition">¶</a></dt>
<dd><p>A collection of values returned by getFloatingIp.</p>
<dl class="py attribute">
<dt id="pulumi_digitalocean.GetFloatingIpResult.id">
<code class="sig-name descname">id</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_digitalocean.GetFloatingIpResult.id" title="Permalink to this definition">¶</a></dt>
<dd><p>The provider-assigned unique ID for this managed resource.</p>
</dd></dl>

</dd></dl>

<dl class="py class">
<dt id="pulumi_digitalocean.GetImageResult">
<em class="property">class </em><code class="sig-prename descclassname">pulumi_digitalocean.</code><code class="sig-name descname">GetImageResult</code><span class="sig-paren">(</span><em class="sig-param"><span class="n">created</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">distribution</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">error_message</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">id</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">image</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">min_disk_size</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">name</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">private</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">regions</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">size_gigabytes</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">slug</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">source</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">status</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">tags</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">type</span><span class="o">=</span><span class="default_value">None</span></em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_digitalocean.GetImageResult" title="Permalink to this definition">¶</a></dt>
<dd><p>A collection of values returned by getImage.</p>
<dl class="py attribute">
<dt id="pulumi_digitalocean.GetImageResult.distribution">
<code class="sig-name descname">distribution</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_digitalocean.GetImageResult.distribution" title="Permalink to this definition">¶</a></dt>
<dd><p>The name of the distribution of the OS of the image.</p>
<ul class="simple">
<li><p><code class="docutils literal notranslate"><span class="pre">min_disk_size</span></code>: The minimum ‘disk’ required for the image.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">size_gigabytes</span></code>: The size of the image in GB.</p></li>
</ul>
</dd></dl>

<dl class="py attribute">
<dt id="pulumi_digitalocean.GetImageResult.image">
<code class="sig-name descname">image</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_digitalocean.GetImageResult.image" title="Permalink to this definition">¶</a></dt>
<dd><p>The id of the image (legacy parameter).</p>
</dd></dl>

<dl class="py attribute">
<dt id="pulumi_digitalocean.GetImageResult.private">
<code class="sig-name descname">private</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_digitalocean.GetImageResult.private" title="Permalink to this definition">¶</a></dt>
<dd><p>Is image a public image or not. Public images represent
Linux distributions or One-Click Applications, while non-public images represent
snapshots and backups and are only available within your account.</p>
<ul class="simple">
<li><p><code class="docutils literal notranslate"><span class="pre">regions</span></code>: A set of the regions that the image is available in.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">tags</span></code>: A set of tags applied to the image</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">created</span></code>: When the image was created</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">status</span></code>: Current status of the image</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">error_message</span></code>: Any applicable error message pertaining to the image</p></li>
</ul>
</dd></dl>

</dd></dl>

<dl class="py class">
<dt id="pulumi_digitalocean.GetImagesResult">
<em class="property">class </em><code class="sig-prename descclassname">pulumi_digitalocean.</code><code class="sig-name descname">GetImagesResult</code><span class="sig-paren">(</span><em class="sig-param"><span class="n">filters</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">id</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">images</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">sorts</span><span class="o">=</span><span class="default_value">None</span></em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_digitalocean.GetImagesResult" title="Permalink to this definition">¶</a></dt>
<dd><p>A collection of values returned by getImages.</p>
<dl class="py attribute">
<dt id="pulumi_digitalocean.GetImagesResult.id">
<code class="sig-name descname">id</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_digitalocean.GetImagesResult.id" title="Permalink to this definition">¶</a></dt>
<dd><p>The provider-assigned unique ID for this managed resource.</p>
</dd></dl>

<dl class="py attribute">
<dt id="pulumi_digitalocean.GetImagesResult.images">
<code class="sig-name descname">images</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_digitalocean.GetImagesResult.images" title="Permalink to this definition">¶</a></dt>
<dd><p>A set of images satisfying any <code class="docutils literal notranslate"><span class="pre">filter</span></code> and <code class="docutils literal notranslate"><span class="pre">sort</span></code> criteria. Each image has the following attributes:</p>
<ul class="simple">
<li><p><code class="docutils literal notranslate"><span class="pre">slug</span></code>: Unique text identifier of the image.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">id</span></code>: The ID of the image.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">name</span></code>: The name of the image.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">type</span></code>: Type of the image.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">distribution</span></code> - The name of the distribution of the OS of the image.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">min_disk_size</span></code>: The minimum ‘disk’ required for the image.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">size_gigabytes</span></code>: The size of the image in GB.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">private</span></code> - Is image a public image or not. Public images represent
Linux distributions or One-Click Applications, while non-public images represent
snapshots and backups and are only available within your account.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">regions</span></code>: A set of the regions that the image is available in.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">tags</span></code>: A set of tags applied to the image</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">created</span></code>: When the image was created</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">status</span></code>: Current status of the image</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">error_message</span></code>: Any applicable error message pertaining to the image</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">image</span></code> - The id of the image (legacy parameter).</p></li>
</ul>
</dd></dl>

</dd></dl>

<dl class="py class">
<dt id="pulumi_digitalocean.GetKubernetesClusterResult">
<em class="property">class </em><code class="sig-prename descclassname">pulumi_digitalocean.</code><code class="sig-name descname">GetKubernetesClusterResult</code><span class="sig-paren">(</span><em class="sig-param"><span class="n">cluster_subnet</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">created_at</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">endpoint</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">id</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">ipv4_address</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">kube_configs</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">name</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">node_pools</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">region</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">service_subnet</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">status</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">tags</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">updated_at</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">version</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">vpc_uuid</span><span class="o">=</span><span class="default_value">None</span></em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_digitalocean.GetKubernetesClusterResult" title="Permalink to this definition">¶</a></dt>
<dd><p>A collection of values returned by getKubernetesCluster.</p>
<dl class="py attribute">
<dt id="pulumi_digitalocean.GetKubernetesClusterResult.cluster_subnet">
<code class="sig-name descname">cluster_subnet</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_digitalocean.GetKubernetesClusterResult.cluster_subnet" title="Permalink to this definition">¶</a></dt>
<dd><p>The range of IP addresses in the overlay network of the Kubernetes cluster.</p>
</dd></dl>

<dl class="py attribute">
<dt id="pulumi_digitalocean.GetKubernetesClusterResult.created_at">
<code class="sig-name descname">created_at</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_digitalocean.GetKubernetesClusterResult.created_at" title="Permalink to this definition">¶</a></dt>
<dd><p>The date and time when the Kubernetes cluster was created.</p>
</dd></dl>

<dl class="py attribute">
<dt id="pulumi_digitalocean.GetKubernetesClusterResult.endpoint">
<code class="sig-name descname">endpoint</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_digitalocean.GetKubernetesClusterResult.endpoint" title="Permalink to this definition">¶</a></dt>
<dd><p>The base URL of the API server on the Kubernetes master node.</p>
</dd></dl>

<dl class="py attribute">
<dt id="pulumi_digitalocean.GetKubernetesClusterResult.id">
<code class="sig-name descname">id</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_digitalocean.GetKubernetesClusterResult.id" title="Permalink to this definition">¶</a></dt>
<dd><p>The provider-assigned unique ID for this managed resource.</p>
</dd></dl>

<dl class="py attribute">
<dt id="pulumi_digitalocean.GetKubernetesClusterResult.ipv4_address">
<code class="sig-name descname">ipv4_address</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_digitalocean.GetKubernetesClusterResult.ipv4_address" title="Permalink to this definition">¶</a></dt>
<dd><p>The public IPv4 address of the Kubernetes master node.</p>
</dd></dl>

<dl class="py attribute">
<dt id="pulumi_digitalocean.GetKubernetesClusterResult.node_pools">
<code class="sig-name descname">node_pools</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_digitalocean.GetKubernetesClusterResult.node_pools" title="Permalink to this definition">¶</a></dt>
<dd><p>A list of node pools associated with the cluster. Each node pool exports the following attributes:</p>
<ul class="simple">
<li><p><code class="docutils literal notranslate"><span class="pre">id</span></code> -  The unique ID that can be used to identify and reference the node pool.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">name</span></code> - The name of the node pool.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">size</span></code> - The slug identifier for the type of Droplet used as workers in the node pool.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">node_count</span></code> - The number of Droplet instances in the node pool.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">actual_node_count</span></code> - The actual number of nodes in the node pool, which is especially useful when auto-scaling is enabled.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">auto_scale</span></code> - A boolean indicating whether auto-scaling is enabled on the node pool.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">min_nodes</span></code> - If auto-scaling is enabled, this represents the minimum number of nodes that the node pool can be scaled down to.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">max_nodes</span></code> - If auto-scaling is enabled, this represents the maximum number of nodes that the node pool can be scaled up to.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">tags</span></code> - A list of tag names applied to the node pool.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">labels</span></code> - A map of key/value pairs applied to nodes in the pool. The labels are exposed in the Kubernetes API as labels in the metadata of the corresponding <a class="reference external" href="https://kubernetes.io/docs/concepts/architecture/nodes/">Node resources</a>.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">nodes</span></code> - A list of nodes in the pool. Each node exports the following attributes:</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">id</span></code> -  A unique ID that can be used to identify and reference the node.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">name</span></code> - The auto-generated name for the node.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">status</span></code> -  A string indicating the current status of the individual node.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">created_at</span></code> - The date and time when the node was created.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">updated_at</span></code> - The date and time when the node was last updated.</p></li>
</ul>
</dd></dl>

<dl class="py attribute">
<dt id="pulumi_digitalocean.GetKubernetesClusterResult.region">
<code class="sig-name descname">region</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_digitalocean.GetKubernetesClusterResult.region" title="Permalink to this definition">¶</a></dt>
<dd><p>The slug identifier for the region where the Kubernetes cluster is located.</p>
</dd></dl>

<dl class="py attribute">
<dt id="pulumi_digitalocean.GetKubernetesClusterResult.service_subnet">
<code class="sig-name descname">service_subnet</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_digitalocean.GetKubernetesClusterResult.service_subnet" title="Permalink to this definition">¶</a></dt>
<dd><p>The range of assignable IP addresses for services running in the Kubernetes cluster.</p>
</dd></dl>

<dl class="py attribute">
<dt id="pulumi_digitalocean.GetKubernetesClusterResult.status">
<code class="sig-name descname">status</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_digitalocean.GetKubernetesClusterResult.status" title="Permalink to this definition">¶</a></dt>
<dd><p>A string indicating the current status of the cluster. Potential values include running, provisioning, and errored.</p>
</dd></dl>

<dl class="py attribute">
<dt id="pulumi_digitalocean.GetKubernetesClusterResult.tags">
<code class="sig-name descname">tags</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_digitalocean.GetKubernetesClusterResult.tags" title="Permalink to this definition">¶</a></dt>
<dd><p>A list of tag names to be applied to the Kubernetes cluster.</p>
</dd></dl>

<dl class="py attribute">
<dt id="pulumi_digitalocean.GetKubernetesClusterResult.updated_at">
<code class="sig-name descname">updated_at</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_digitalocean.GetKubernetesClusterResult.updated_at" title="Permalink to this definition">¶</a></dt>
<dd><p>The date and time when the Kubernetes cluster was last updated.</p>
<ul class="simple">
<li><p><code class="docutils literal notranslate"><span class="pre">kube_config.0</span></code> - A representation of the Kubernetes cluster’s kubeconfig with the following attributes:</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">raw_config</span></code> - The full contents of the Kubernetes cluster’s kubeconfig file.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">host</span></code> - The URL of the API server on the Kubernetes master node.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">cluster_ca_certificate</span></code> - The base64 encoded public certificate for the cluster’s certificate authority.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">token</span></code> - The DigitalOcean API access token used by clients to access the cluster.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">client_key</span></code> - The base64 encoded private key used by clients to access the cluster. Only available if token authentication is not supported on your cluster.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">client_certificate</span></code> - The base64 encoded public certificate used by clients to access the cluster. Only available if token authentication is not supported on your cluster.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">expires_at</span></code> - The date and time when the credentials will expire and need to be regenerated.</p></li>
</ul>
</dd></dl>

<dl class="py attribute">
<dt id="pulumi_digitalocean.GetKubernetesClusterResult.version">
<code class="sig-name descname">version</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_digitalocean.GetKubernetesClusterResult.version" title="Permalink to this definition">¶</a></dt>
<dd><p>The slug identifier for the version of Kubernetes used for the cluster.</p>
</dd></dl>

<dl class="py attribute">
<dt id="pulumi_digitalocean.GetKubernetesClusterResult.vpc_uuid">
<code class="sig-name descname">vpc_uuid</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_digitalocean.GetKubernetesClusterResult.vpc_uuid" title="Permalink to this definition">¶</a></dt>
<dd><p>The ID of the VPC where the Kubernetes cluster is located.</p>
</dd></dl>

</dd></dl>

<dl class="py class">
<dt id="pulumi_digitalocean.GetKubernetesVersionsResult">
<em class="property">class </em><code class="sig-prename descclassname">pulumi_digitalocean.</code><code class="sig-name descname">GetKubernetesVersionsResult</code><span class="sig-paren">(</span><em class="sig-param"><span class="n">id</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">latest_version</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">valid_versions</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">version_prefix</span><span class="o">=</span><span class="default_value">None</span></em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_digitalocean.GetKubernetesVersionsResult" title="Permalink to this definition">¶</a></dt>
<dd><p>A collection of values returned by getKubernetesVersions.</p>
<dl class="py attribute">
<dt id="pulumi_digitalocean.GetKubernetesVersionsResult.id">
<code class="sig-name descname">id</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_digitalocean.GetKubernetesVersionsResult.id" title="Permalink to this definition">¶</a></dt>
<dd><p>The provider-assigned unique ID for this managed resource.</p>
</dd></dl>

<dl class="py attribute">
<dt id="pulumi_digitalocean.GetKubernetesVersionsResult.latest_version">
<code class="sig-name descname">latest_version</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_digitalocean.GetKubernetesVersionsResult.latest_version" title="Permalink to this definition">¶</a></dt>
<dd><p>The most recent version available.</p>
</dd></dl>

<dl class="py attribute">
<dt id="pulumi_digitalocean.GetKubernetesVersionsResult.valid_versions">
<code class="sig-name descname">valid_versions</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_digitalocean.GetKubernetesVersionsResult.valid_versions" title="Permalink to this definition">¶</a></dt>
<dd><p>A list of available versions.</p>
</dd></dl>

</dd></dl>

<dl class="py class">
<dt id="pulumi_digitalocean.GetLoadBalancerResult">
<em class="property">class </em><code class="sig-prename descclassname">pulumi_digitalocean.</code><code class="sig-name descname">GetLoadBalancerResult</code><span class="sig-paren">(</span><em class="sig-param"><span class="n">algorithm</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">droplet_ids</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">droplet_tag</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">enable_backend_keepalive</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">enable_proxy_protocol</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">forwarding_rules</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">healthcheck</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">id</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">ip</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">name</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">redirect_http_to_https</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">region</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">status</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">sticky_sessions</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">urn</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">vpc_uuid</span><span class="o">=</span><span class="default_value">None</span></em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_digitalocean.GetLoadBalancerResult" title="Permalink to this definition">¶</a></dt>
<dd><p>A collection of values returned by getLoadBalancer.</p>
<dl class="py attribute">
<dt id="pulumi_digitalocean.GetLoadBalancerResult.id">
<code class="sig-name descname">id</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_digitalocean.GetLoadBalancerResult.id" title="Permalink to this definition">¶</a></dt>
<dd><p>The provider-assigned unique ID for this managed resource.</p>
</dd></dl>

</dd></dl>

<dl class="py class">
<dt id="pulumi_digitalocean.GetProjectResult">
<em class="property">class </em><code class="sig-prename descclassname">pulumi_digitalocean.</code><code class="sig-name descname">GetProjectResult</code><span class="sig-paren">(</span><em class="sig-param"><span class="n">created_at</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">description</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">environment</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">id</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">is_default</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">name</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">owner_id</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">owner_uuid</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">purpose</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">resources</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">updated_at</span><span class="o">=</span><span class="default_value">None</span></em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_digitalocean.GetProjectResult" title="Permalink to this definition">¶</a></dt>
<dd><p>A collection of values returned by getProject.</p>
<dl class="py attribute">
<dt id="pulumi_digitalocean.GetProjectResult.created_at">
<code class="sig-name descname">created_at</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_digitalocean.GetProjectResult.created_at" title="Permalink to this definition">¶</a></dt>
<dd><p>The date and time when the project was created, (ISO8601)</p>
</dd></dl>

<dl class="py attribute">
<dt id="pulumi_digitalocean.GetProjectResult.description">
<code class="sig-name descname">description</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_digitalocean.GetProjectResult.description" title="Permalink to this definition">¶</a></dt>
<dd><p>The description of the project</p>
</dd></dl>

<dl class="py attribute">
<dt id="pulumi_digitalocean.GetProjectResult.environment">
<code class="sig-name descname">environment</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_digitalocean.GetProjectResult.environment" title="Permalink to this definition">¶</a></dt>
<dd><p>The environment of the project’s resources. The possible values are: <code class="docutils literal notranslate"><span class="pre">Development</span></code>, <code class="docutils literal notranslate"><span class="pre">Staging</span></code>, <code class="docutils literal notranslate"><span class="pre">Production</span></code>.</p>
</dd></dl>

<dl class="py attribute">
<dt id="pulumi_digitalocean.GetProjectResult.owner_id">
<code class="sig-name descname">owner_id</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_digitalocean.GetProjectResult.owner_id" title="Permalink to this definition">¶</a></dt>
<dd><p>The ID of the project owner.</p>
</dd></dl>

<dl class="py attribute">
<dt id="pulumi_digitalocean.GetProjectResult.owner_uuid">
<code class="sig-name descname">owner_uuid</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_digitalocean.GetProjectResult.owner_uuid" title="Permalink to this definition">¶</a></dt>
<dd><p>The unique universal identifier of the project owner.</p>
</dd></dl>

<dl class="py attribute">
<dt id="pulumi_digitalocean.GetProjectResult.purpose">
<code class="sig-name descname">purpose</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_digitalocean.GetProjectResult.purpose" title="Permalink to this definition">¶</a></dt>
<dd><p>The purpose of the project, (Default: “Web Application”)</p>
</dd></dl>

<dl class="py attribute">
<dt id="pulumi_digitalocean.GetProjectResult.resources">
<code class="sig-name descname">resources</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_digitalocean.GetProjectResult.resources" title="Permalink to this definition">¶</a></dt>
<dd><p>A set of uniform resource names (URNs) for the resources associated with the project</p>
</dd></dl>

<dl class="py attribute">
<dt id="pulumi_digitalocean.GetProjectResult.updated_at">
<code class="sig-name descname">updated_at</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_digitalocean.GetProjectResult.updated_at" title="Permalink to this definition">¶</a></dt>
<dd><p>The date and time when the project was last updated, (ISO8601)</p>
</dd></dl>

</dd></dl>

<dl class="py class">
<dt id="pulumi_digitalocean.GetProjectsResult">
<em class="property">class </em><code class="sig-prename descclassname">pulumi_digitalocean.</code><code class="sig-name descname">GetProjectsResult</code><span class="sig-paren">(</span><em class="sig-param"><span class="n">filters</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">id</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">projects</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">sorts</span><span class="o">=</span><span class="default_value">None</span></em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_digitalocean.GetProjectsResult" title="Permalink to this definition">¶</a></dt>
<dd><p>A collection of values returned by getProjects.</p>
<dl class="py attribute">
<dt id="pulumi_digitalocean.GetProjectsResult.id">
<code class="sig-name descname">id</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_digitalocean.GetProjectsResult.id" title="Permalink to this definition">¶</a></dt>
<dd><p>The provider-assigned unique ID for this managed resource.</p>
</dd></dl>

<dl class="py attribute">
<dt id="pulumi_digitalocean.GetProjectsResult.projects">
<code class="sig-name descname">projects</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_digitalocean.GetProjectsResult.projects" title="Permalink to this definition">¶</a></dt>
<dd><p>A set of projects satisfying any <code class="docutils literal notranslate"><span class="pre">filter</span></code> and <code class="docutils literal notranslate"><span class="pre">sort</span></code> criteria. Each project has
the following attributes:</p>
<ul class="simple">
<li><p><code class="docutils literal notranslate"><span class="pre">id</span></code> - The ID of the project</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">name</span></code> - The name of the project</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">description</span></code> - The description of the project</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">purpose</span></code> -  The purpose of the project (Default: “Web Application”)</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">environment</span></code> - The environment of the project’s resources. The possible values are: <code class="docutils literal notranslate"><span class="pre">Development</span></code>, <code class="docutils literal notranslate"><span class="pre">Staging</span></code>, <code class="docutils literal notranslate"><span class="pre">Production</span></code>.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">resources</span></code> - A set of uniform resource names (URNs) for the resources associated with the project</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">owner_uuid</span></code> - The unique universal identifier of the project owner</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">owner_id</span></code> - The ID of the project owner</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">created_at</span></code> - The date and time when the project was created, (ISO8601)</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">updated_at</span></code> - The date and time when the project was last updated, (ISO8601)</p></li>
</ul>
</dd></dl>

</dd></dl>

<dl class="py class">
<dt id="pulumi_digitalocean.GetRecordResult">
<em class="property">class </em><code class="sig-prename descclassname">pulumi_digitalocean.</code><code class="sig-name descname">GetRecordResult</code><span class="sig-paren">(</span><em class="sig-param"><span class="n">data</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">domain</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">flags</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">id</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">name</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">port</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">priority</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">tag</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">ttl</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">type</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">weight</span><span class="o">=</span><span class="default_value">None</span></em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_digitalocean.GetRecordResult" title="Permalink to this definition">¶</a></dt>
<dd><p>A collection of values returned by getRecord.</p>
<dl class="py attribute">
<dt id="pulumi_digitalocean.GetRecordResult.id">
<code class="sig-name descname">id</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_digitalocean.GetRecordResult.id" title="Permalink to this definition">¶</a></dt>
<dd><p>The provider-assigned unique ID for this managed resource.</p>
</dd></dl>

</dd></dl>

<dl class="py class">
<dt id="pulumi_digitalocean.GetRegionResult">
<em class="property">class </em><code class="sig-prename descclassname">pulumi_digitalocean.</code><code class="sig-name descname">GetRegionResult</code><span class="sig-paren">(</span><em class="sig-param"><span class="n">available</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">features</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">id</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">name</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">sizes</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">slug</span><span class="o">=</span><span class="default_value">None</span></em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_digitalocean.GetRegionResult" title="Permalink to this definition">¶</a></dt>
<dd><p>A collection of values returned by getRegion.</p>
<dl class="py attribute">
<dt id="pulumi_digitalocean.GetRegionResult.available">
<code class="sig-name descname">available</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_digitalocean.GetRegionResult.available" title="Permalink to this definition">¶</a></dt>
<dd><p>A boolean value that represents whether new Droplets can be created in this region.</p>
</dd></dl>

<dl class="py attribute">
<dt id="pulumi_digitalocean.GetRegionResult.features">
<code class="sig-name descname">features</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_digitalocean.GetRegionResult.features" title="Permalink to this definition">¶</a></dt>
<dd><p>A set of features available in this region.</p>
</dd></dl>

<dl class="py attribute">
<dt id="pulumi_digitalocean.GetRegionResult.id">
<code class="sig-name descname">id</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_digitalocean.GetRegionResult.id" title="Permalink to this definition">¶</a></dt>
<dd><p>The provider-assigned unique ID for this managed resource.</p>
</dd></dl>

<dl class="py attribute">
<dt id="pulumi_digitalocean.GetRegionResult.name">
<code class="sig-name descname">name</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_digitalocean.GetRegionResult.name" title="Permalink to this definition">¶</a></dt>
<dd><p>The display name of the region.</p>
</dd></dl>

<dl class="py attribute">
<dt id="pulumi_digitalocean.GetRegionResult.sizes">
<code class="sig-name descname">sizes</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_digitalocean.GetRegionResult.sizes" title="Permalink to this definition">¶</a></dt>
<dd><p>A set of identifying slugs for the Droplet sizes available in this region.</p>
</dd></dl>

<dl class="py attribute">
<dt id="pulumi_digitalocean.GetRegionResult.slug">
<code class="sig-name descname">slug</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_digitalocean.GetRegionResult.slug" title="Permalink to this definition">¶</a></dt>
<dd><p>A human-readable string that is used as a unique identifier for each region.</p>
</dd></dl>

</dd></dl>

<dl class="py class">
<dt id="pulumi_digitalocean.GetRegionsResult">
<em class="property">class </em><code class="sig-prename descclassname">pulumi_digitalocean.</code><code class="sig-name descname">GetRegionsResult</code><span class="sig-paren">(</span><em class="sig-param"><span class="n">filters</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">id</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">regions</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">sorts</span><span class="o">=</span><span class="default_value">None</span></em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_digitalocean.GetRegionsResult" title="Permalink to this definition">¶</a></dt>
<dd><p>A collection of values returned by getRegions.</p>
<dl class="py attribute">
<dt id="pulumi_digitalocean.GetRegionsResult.id">
<code class="sig-name descname">id</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_digitalocean.GetRegionsResult.id" title="Permalink to this definition">¶</a></dt>
<dd><p>The provider-assigned unique ID for this managed resource.</p>
</dd></dl>

<dl class="py attribute">
<dt id="pulumi_digitalocean.GetRegionsResult.regions">
<code class="sig-name descname">regions</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_digitalocean.GetRegionsResult.regions" title="Permalink to this definition">¶</a></dt>
<dd><p>A set of regions satisfying any <code class="docutils literal notranslate"><span class="pre">filter</span></code> and <code class="docutils literal notranslate"><span class="pre">sort</span></code> criteria. Each region has the following attributes:</p>
<ul class="simple">
<li><p><code class="docutils literal notranslate"><span class="pre">slug</span></code> - A human-readable string that is used as a unique identifier for each region.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">name</span></code> - The display name of the region.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">available</span></code> - A boolean value that represents whether new Droplets can be created in this region.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">sizes</span></code> - A set of identifying slugs for the Droplet sizes available in this region.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">features</span></code> - A set of features available in this region.</p></li>
</ul>
</dd></dl>

</dd></dl>

<dl class="py class">
<dt id="pulumi_digitalocean.GetSizesResult">
<em class="property">class </em><code class="sig-prename descclassname">pulumi_digitalocean.</code><code class="sig-name descname">GetSizesResult</code><span class="sig-paren">(</span><em class="sig-param"><span class="n">filters</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">id</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">sizes</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">sorts</span><span class="o">=</span><span class="default_value">None</span></em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_digitalocean.GetSizesResult" title="Permalink to this definition">¶</a></dt>
<dd><p>A collection of values returned by getSizes.</p>
<dl class="py attribute">
<dt id="pulumi_digitalocean.GetSizesResult.id">
<code class="sig-name descname">id</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_digitalocean.GetSizesResult.id" title="Permalink to this definition">¶</a></dt>
<dd><p>The provider-assigned unique ID for this managed resource.</p>
</dd></dl>

</dd></dl>

<dl class="py class">
<dt id="pulumi_digitalocean.GetSpacesBucketObjectResult">
<em class="property">class </em><code class="sig-prename descclassname">pulumi_digitalocean.</code><code class="sig-name descname">GetSpacesBucketObjectResult</code><span class="sig-paren">(</span><em class="sig-param"><span class="n">body</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">bucket</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">cache_control</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">content_disposition</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">content_encoding</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">content_language</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">content_length</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">content_type</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">etag</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">expiration</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">expires</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">id</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">key</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">last_modified</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">metadata</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">range</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">region</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">version_id</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">website_redirect_location</span><span class="o">=</span><span class="default_value">None</span></em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_digitalocean.GetSpacesBucketObjectResult" title="Permalink to this definition">¶</a></dt>
<dd><p>A collection of values returned by getSpacesBucketObject.</p>
<dl class="py attribute">
<dt id="pulumi_digitalocean.GetSpacesBucketObjectResult.body">
<code class="sig-name descname">body</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_digitalocean.GetSpacesBucketObjectResult.body" title="Permalink to this definition">¶</a></dt>
<dd><p>Object data (see <strong>limitations above</strong> to understand cases in which this field is actually available)</p>
</dd></dl>

<dl class="py attribute">
<dt id="pulumi_digitalocean.GetSpacesBucketObjectResult.cache_control">
<code class="sig-name descname">cache_control</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_digitalocean.GetSpacesBucketObjectResult.cache_control" title="Permalink to this definition">¶</a></dt>
<dd><p>Specifies caching behavior along the request/reply chain.</p>
</dd></dl>

<dl class="py attribute">
<dt id="pulumi_digitalocean.GetSpacesBucketObjectResult.content_disposition">
<code class="sig-name descname">content_disposition</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_digitalocean.GetSpacesBucketObjectResult.content_disposition" title="Permalink to this definition">¶</a></dt>
<dd><p>Specifies presentational information for the object.</p>
</dd></dl>

<dl class="py attribute">
<dt id="pulumi_digitalocean.GetSpacesBucketObjectResult.content_encoding">
<code class="sig-name descname">content_encoding</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_digitalocean.GetSpacesBucketObjectResult.content_encoding" title="Permalink to this definition">¶</a></dt>
<dd><p>Specifies what content encodings have been applied to the object and thus what decoding mechanisms must be applied to obtain the media-type referenced by the Content-Type header field.</p>
</dd></dl>

<dl class="py attribute">
<dt id="pulumi_digitalocean.GetSpacesBucketObjectResult.content_language">
<code class="sig-name descname">content_language</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_digitalocean.GetSpacesBucketObjectResult.content_language" title="Permalink to this definition">¶</a></dt>
<dd><p>The language the content is in.</p>
</dd></dl>

<dl class="py attribute">
<dt id="pulumi_digitalocean.GetSpacesBucketObjectResult.content_length">
<code class="sig-name descname">content_length</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_digitalocean.GetSpacesBucketObjectResult.content_length" title="Permalink to this definition">¶</a></dt>
<dd><p>Size of the body in bytes.</p>
</dd></dl>

<dl class="py attribute">
<dt id="pulumi_digitalocean.GetSpacesBucketObjectResult.content_type">
<code class="sig-name descname">content_type</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_digitalocean.GetSpacesBucketObjectResult.content_type" title="Permalink to this definition">¶</a></dt>
<dd><p>A standard MIME type describing the format of the object data.</p>
</dd></dl>

<dl class="py attribute">
<dt id="pulumi_digitalocean.GetSpacesBucketObjectResult.etag">
<code class="sig-name descname">etag</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_digitalocean.GetSpacesBucketObjectResult.etag" title="Permalink to this definition">¶</a></dt>
<dd><p><a class="reference external" href="https://en.wikipedia.org/wiki/HTTP_ETag">ETag</a> generated for the object (an MD5 sum of the object content in case it’s not encrypted)</p>
</dd></dl>

<dl class="py attribute">
<dt id="pulumi_digitalocean.GetSpacesBucketObjectResult.expiration">
<code class="sig-name descname">expiration</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_digitalocean.GetSpacesBucketObjectResult.expiration" title="Permalink to this definition">¶</a></dt>
<dd><p>If the object expiration is configured (see <a class="reference external" href="http://docs.aws.amazon.com/AmazonS3/latest/dev/object-lifecycle-mgmt.html">object lifecycle management</a>), the field includes this header. It includes the expiry-date and rule-id key value pairs providing object expiration information. The value of the rule-id is URL encoded.</p>
</dd></dl>

<dl class="py attribute">
<dt id="pulumi_digitalocean.GetSpacesBucketObjectResult.expires">
<code class="sig-name descname">expires</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_digitalocean.GetSpacesBucketObjectResult.expires" title="Permalink to this definition">¶</a></dt>
<dd><p>The date and time at which the object is no longer cacheable.</p>
</dd></dl>

<dl class="py attribute">
<dt id="pulumi_digitalocean.GetSpacesBucketObjectResult.id">
<code class="sig-name descname">id</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_digitalocean.GetSpacesBucketObjectResult.id" title="Permalink to this definition">¶</a></dt>
<dd><p>The provider-assigned unique ID for this managed resource.</p>
</dd></dl>

<dl class="py attribute">
<dt id="pulumi_digitalocean.GetSpacesBucketObjectResult.last_modified">
<code class="sig-name descname">last_modified</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_digitalocean.GetSpacesBucketObjectResult.last_modified" title="Permalink to this definition">¶</a></dt>
<dd><p>Last modified date of the object in RFC1123 format (e.g. <code class="docutils literal notranslate"><span class="pre">Mon,</span> <span class="pre">02</span> <span class="pre">Jan</span> <span class="pre">2006</span> <span class="pre">15:04:05</span> <span class="pre">MST</span></code>)</p>
</dd></dl>

<dl class="py attribute">
<dt id="pulumi_digitalocean.GetSpacesBucketObjectResult.metadata">
<code class="sig-name descname">metadata</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_digitalocean.GetSpacesBucketObjectResult.metadata" title="Permalink to this definition">¶</a></dt>
<dd><p>A map of metadata stored with the object in Spaces</p>
</dd></dl>

<dl class="py attribute">
<dt id="pulumi_digitalocean.GetSpacesBucketObjectResult.version_id">
<code class="sig-name descname">version_id</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_digitalocean.GetSpacesBucketObjectResult.version_id" title="Permalink to this definition">¶</a></dt>
<dd><p>The latest version ID of the object returned.</p>
</dd></dl>

<dl class="py attribute">
<dt id="pulumi_digitalocean.GetSpacesBucketObjectResult.website_redirect_location">
<code class="sig-name descname">website_redirect_location</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_digitalocean.GetSpacesBucketObjectResult.website_redirect_location" title="Permalink to this definition">¶</a></dt>
<dd><p>If the bucket is configured as a website, redirects requests for this object to another object in the same bucket or to an external URL. Spaces stores the value of this header in the object metadata.</p>
</dd></dl>

</dd></dl>

<dl class="py class">
<dt id="pulumi_digitalocean.GetSpacesBucketObjectsResult">
<em class="property">class </em><code class="sig-prename descclassname">pulumi_digitalocean.</code><code class="sig-name descname">GetSpacesBucketObjectsResult</code><span class="sig-paren">(</span><em class="sig-param"><span class="n">bucket</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">common_prefixes</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">delimiter</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">encoding_type</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">id</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">keys</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">max_keys</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">owners</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">prefix</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">region</span><span class="o">=</span><span class="default_value">None</span></em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_digitalocean.GetSpacesBucketObjectsResult" title="Permalink to this definition">¶</a></dt>
<dd><p>A collection of values returned by getSpacesBucketObjects.</p>
<dl class="py attribute">
<dt id="pulumi_digitalocean.GetSpacesBucketObjectsResult.common_prefixes">
<code class="sig-name descname">common_prefixes</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_digitalocean.GetSpacesBucketObjectsResult.common_prefixes" title="Permalink to this definition">¶</a></dt>
<dd><p>List of any keys between <code class="docutils literal notranslate"><span class="pre">prefix</span></code> and the next occurrence of <code class="docutils literal notranslate"><span class="pre">delimiter</span></code> (i.e., similar to subdirectories of the <code class="docutils literal notranslate"><span class="pre">prefix</span></code> “directory”); the list is only returned when you specify <code class="docutils literal notranslate"><span class="pre">delimiter</span></code></p>
</dd></dl>

<dl class="py attribute">
<dt id="pulumi_digitalocean.GetSpacesBucketObjectsResult.id">
<code class="sig-name descname">id</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_digitalocean.GetSpacesBucketObjectsResult.id" title="Permalink to this definition">¶</a></dt>
<dd><p>The provider-assigned unique ID for this managed resource.</p>
</dd></dl>

<dl class="py attribute">
<dt id="pulumi_digitalocean.GetSpacesBucketObjectsResult.keys">
<code class="sig-name descname">keys</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_digitalocean.GetSpacesBucketObjectsResult.keys" title="Permalink to this definition">¶</a></dt>
<dd><p>List of strings representing object keys</p>
</dd></dl>

<dl class="py attribute">
<dt id="pulumi_digitalocean.GetSpacesBucketObjectsResult.owners">
<code class="sig-name descname">owners</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_digitalocean.GetSpacesBucketObjectsResult.owners" title="Permalink to this definition">¶</a></dt>
<dd><p>List of strings representing object owner IDs</p>
</dd></dl>

</dd></dl>

<dl class="py class">
<dt id="pulumi_digitalocean.GetSpacesBucketResult">
<em class="property">class </em><code class="sig-prename descclassname">pulumi_digitalocean.</code><code class="sig-name descname">GetSpacesBucketResult</code><span class="sig-paren">(</span><em class="sig-param"><span class="n">bucket_domain_name</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">id</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">name</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">region</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">urn</span><span class="o">=</span><span class="default_value">None</span></em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_digitalocean.GetSpacesBucketResult" title="Permalink to this definition">¶</a></dt>
<dd><p>A collection of values returned by getSpacesBucket.</p>
<dl class="py attribute">
<dt id="pulumi_digitalocean.GetSpacesBucketResult.bucket_domain_name">
<code class="sig-name descname">bucket_domain_name</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_digitalocean.GetSpacesBucketResult.bucket_domain_name" title="Permalink to this definition">¶</a></dt>
<dd><p>The FQDN of the bucket (e.g. bucket-name.nyc3.digitaloceanspaces.com)</p>
</dd></dl>

<dl class="py attribute">
<dt id="pulumi_digitalocean.GetSpacesBucketResult.id">
<code class="sig-name descname">id</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_digitalocean.GetSpacesBucketResult.id" title="Permalink to this definition">¶</a></dt>
<dd><p>The provider-assigned unique ID for this managed resource.</p>
</dd></dl>

<dl class="py attribute">
<dt id="pulumi_digitalocean.GetSpacesBucketResult.name">
<code class="sig-name descname">name</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_digitalocean.GetSpacesBucketResult.name" title="Permalink to this definition">¶</a></dt>
<dd><p>The name of the Spaces bucket</p>
</dd></dl>

<dl class="py attribute">
<dt id="pulumi_digitalocean.GetSpacesBucketResult.region">
<code class="sig-name descname">region</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_digitalocean.GetSpacesBucketResult.region" title="Permalink to this definition">¶</a></dt>
<dd><p>The slug of the region where the bucket is stored.</p>
</dd></dl>

<dl class="py attribute">
<dt id="pulumi_digitalocean.GetSpacesBucketResult.urn">
<code class="sig-name descname">urn</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_digitalocean.GetSpacesBucketResult.urn" title="Permalink to this definition">¶</a></dt>
<dd><p>The uniform resource name of the bucket</p>
</dd></dl>

</dd></dl>

<dl class="py class">
<dt id="pulumi_digitalocean.GetSpacesBucketsResult">
<em class="property">class </em><code class="sig-prename descclassname">pulumi_digitalocean.</code><code class="sig-name descname">GetSpacesBucketsResult</code><span class="sig-paren">(</span><em class="sig-param"><span class="n">buckets</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">filters</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">id</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">sorts</span><span class="o">=</span><span class="default_value">None</span></em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_digitalocean.GetSpacesBucketsResult" title="Permalink to this definition">¶</a></dt>
<dd><p>A collection of values returned by getSpacesBuckets.</p>
<dl class="py attribute">
<dt id="pulumi_digitalocean.GetSpacesBucketsResult.buckets">
<code class="sig-name descname">buckets</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_digitalocean.GetSpacesBucketsResult.buckets" title="Permalink to this definition">¶</a></dt>
<dd><p>A list of Spaces buckets satisfying any <code class="docutils literal notranslate"><span class="pre">filter</span></code> and <code class="docutils literal notranslate"><span class="pre">sort</span></code> criteria. Each bucket has the following attributes:</p>
</dd></dl>

<dl class="py attribute">
<dt id="pulumi_digitalocean.GetSpacesBucketsResult.id">
<code class="sig-name descname">id</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_digitalocean.GetSpacesBucketsResult.id" title="Permalink to this definition">¶</a></dt>
<dd><p>The provider-assigned unique ID for this managed resource.</p>
</dd></dl>

</dd></dl>

<dl class="py class">
<dt id="pulumi_digitalocean.GetSshKeyResult">
<em class="property">class </em><code class="sig-prename descclassname">pulumi_digitalocean.</code><code class="sig-name descname">GetSshKeyResult</code><span class="sig-paren">(</span><em class="sig-param"><span class="n">fingerprint</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">id</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">name</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">public_key</span><span class="o">=</span><span class="default_value">None</span></em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_digitalocean.GetSshKeyResult" title="Permalink to this definition">¶</a></dt>
<dd><p>A collection of values returned by getSshKey.</p>
<dl class="py attribute">
<dt id="pulumi_digitalocean.GetSshKeyResult.id">
<code class="sig-name descname">id</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_digitalocean.GetSshKeyResult.id" title="Permalink to this definition">¶</a></dt>
<dd><p>The provider-assigned unique ID for this managed resource.</p>
</dd></dl>

</dd></dl>

<dl class="py class">
<dt id="pulumi_digitalocean.GetTagResult">
<em class="property">class </em><code class="sig-prename descclassname">pulumi_digitalocean.</code><code class="sig-name descname">GetTagResult</code><span class="sig-paren">(</span><em class="sig-param"><span class="n">id</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">name</span><span class="o">=</span><span class="default_value">None</span></em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_digitalocean.GetTagResult" title="Permalink to this definition">¶</a></dt>
<dd><p>A collection of values returned by getTag.</p>
<dl class="py attribute">
<dt id="pulumi_digitalocean.GetTagResult.id">
<code class="sig-name descname">id</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_digitalocean.GetTagResult.id" title="Permalink to this definition">¶</a></dt>
<dd><p>The provider-assigned unique ID for this managed resource.</p>
</dd></dl>

</dd></dl>

<dl class="py class">
<dt id="pulumi_digitalocean.GetVolumeResult">
<em class="property">class </em><code class="sig-prename descclassname">pulumi_digitalocean.</code><code class="sig-name descname">GetVolumeResult</code><span class="sig-paren">(</span><em class="sig-param"><span class="n">description</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">droplet_ids</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">filesystem_label</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">filesystem_type</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">id</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">name</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">region</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">size</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">tags</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">urn</span><span class="o">=</span><span class="default_value">None</span></em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_digitalocean.GetVolumeResult" title="Permalink to this definition">¶</a></dt>
<dd><p>A collection of values returned by getVolume.</p>
<dl class="py attribute">
<dt id="pulumi_digitalocean.GetVolumeResult.description">
<code class="sig-name descname">description</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_digitalocean.GetVolumeResult.description" title="Permalink to this definition">¶</a></dt>
<dd><p>Text describing a block storage volume.</p>
</dd></dl>

<dl class="py attribute">
<dt id="pulumi_digitalocean.GetVolumeResult.droplet_ids">
<code class="sig-name descname">droplet_ids</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_digitalocean.GetVolumeResult.droplet_ids" title="Permalink to this definition">¶</a></dt>
<dd><p>A list of associated Droplet ids.</p>
</dd></dl>

<dl class="py attribute">
<dt id="pulumi_digitalocean.GetVolumeResult.filesystem_label">
<code class="sig-name descname">filesystem_label</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_digitalocean.GetVolumeResult.filesystem_label" title="Permalink to this definition">¶</a></dt>
<dd><p>Filesystem label currently in-use on the block storage volume.</p>
</dd></dl>

<dl class="py attribute">
<dt id="pulumi_digitalocean.GetVolumeResult.filesystem_type">
<code class="sig-name descname">filesystem_type</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_digitalocean.GetVolumeResult.filesystem_type" title="Permalink to this definition">¶</a></dt>
<dd><p>Filesystem type currently in-use on the block storage volume.</p>
</dd></dl>

<dl class="py attribute">
<dt id="pulumi_digitalocean.GetVolumeResult.id">
<code class="sig-name descname">id</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_digitalocean.GetVolumeResult.id" title="Permalink to this definition">¶</a></dt>
<dd><p>The provider-assigned unique ID for this managed resource.</p>
</dd></dl>

<dl class="py attribute">
<dt id="pulumi_digitalocean.GetVolumeResult.size">
<code class="sig-name descname">size</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_digitalocean.GetVolumeResult.size" title="Permalink to this definition">¶</a></dt>
<dd><p>The size of the block storage volume in GiB.</p>
</dd></dl>

<dl class="py attribute">
<dt id="pulumi_digitalocean.GetVolumeResult.tags">
<code class="sig-name descname">tags</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_digitalocean.GetVolumeResult.tags" title="Permalink to this definition">¶</a></dt>
<dd><p>A list of the tags associated to the Volume.</p>
</dd></dl>

</dd></dl>

<dl class="py class">
<dt id="pulumi_digitalocean.GetVolumeSnapshotResult">
<em class="property">class </em><code class="sig-prename descclassname">pulumi_digitalocean.</code><code class="sig-name descname">GetVolumeSnapshotResult</code><span class="sig-paren">(</span><em class="sig-param"><span class="n">created_at</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">id</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">min_disk_size</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">most_recent</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">name</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">name_regex</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">region</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">regions</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">size</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">tags</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">volume_id</span><span class="o">=</span><span class="default_value">None</span></em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_digitalocean.GetVolumeSnapshotResult" title="Permalink to this definition">¶</a></dt>
<dd><p>A collection of values returned by getVolumeSnapshot.</p>
<dl class="py attribute">
<dt id="pulumi_digitalocean.GetVolumeSnapshotResult.created_at">
<code class="sig-name descname">created_at</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_digitalocean.GetVolumeSnapshotResult.created_at" title="Permalink to this definition">¶</a></dt>
<dd><p>The date and time the volume snapshot was created.</p>
</dd></dl>

<dl class="py attribute">
<dt id="pulumi_digitalocean.GetVolumeSnapshotResult.id">
<code class="sig-name descname">id</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_digitalocean.GetVolumeSnapshotResult.id" title="Permalink to this definition">¶</a></dt>
<dd><p>The provider-assigned unique ID for this managed resource.</p>
</dd></dl>

<dl class="py attribute">
<dt id="pulumi_digitalocean.GetVolumeSnapshotResult.min_disk_size">
<code class="sig-name descname">min_disk_size</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_digitalocean.GetVolumeSnapshotResult.min_disk_size" title="Permalink to this definition">¶</a></dt>
<dd><p>The minimum size in gigabytes required for a volume to be created based on this volume snapshot.</p>
</dd></dl>

<dl class="py attribute">
<dt id="pulumi_digitalocean.GetVolumeSnapshotResult.regions">
<code class="sig-name descname">regions</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_digitalocean.GetVolumeSnapshotResult.regions" title="Permalink to this definition">¶</a></dt>
<dd><p>A list of DigitalOcean region “slugs” indicating where the volume snapshot is available.</p>
</dd></dl>

<dl class="py attribute">
<dt id="pulumi_digitalocean.GetVolumeSnapshotResult.size">
<code class="sig-name descname">size</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_digitalocean.GetVolumeSnapshotResult.size" title="Permalink to this definition">¶</a></dt>
<dd><p>The billable size of the volume snapshot in gigabytes.</p>
</dd></dl>

<dl class="py attribute">
<dt id="pulumi_digitalocean.GetVolumeSnapshotResult.tags">
<code class="sig-name descname">tags</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_digitalocean.GetVolumeSnapshotResult.tags" title="Permalink to this definition">¶</a></dt>
<dd><p>A list of the tags associated to the volume snapshot.</p>
</dd></dl>

<dl class="py attribute">
<dt id="pulumi_digitalocean.GetVolumeSnapshotResult.volume_id">
<code class="sig-name descname">volume_id</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_digitalocean.GetVolumeSnapshotResult.volume_id" title="Permalink to this definition">¶</a></dt>
<dd><p>The ID of the volume from which the volume snapshot originated.</p>
</dd></dl>

</dd></dl>

<dl class="py class">
<dt id="pulumi_digitalocean.GetVpcResult">
<em class="property">class </em><code class="sig-prename descclassname">pulumi_digitalocean.</code><code class="sig-name descname">GetVpcResult</code><span class="sig-paren">(</span><em class="sig-param"><span class="n">created_at</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">default</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">description</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">id</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">ip_range</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">name</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">region</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">urn</span><span class="o">=</span><span class="default_value">None</span></em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_digitalocean.GetVpcResult" title="Permalink to this definition">¶</a></dt>
<dd><p>A collection of values returned by getVpc.</p>
<dl class="py attribute">
<dt id="pulumi_digitalocean.GetVpcResult.created_at">
<code class="sig-name descname">created_at</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_digitalocean.GetVpcResult.created_at" title="Permalink to this definition">¶</a></dt>
<dd><p>The date and time of when the VPC was created.</p>
</dd></dl>

<dl class="py attribute">
<dt id="pulumi_digitalocean.GetVpcResult.default">
<code class="sig-name descname">default</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_digitalocean.GetVpcResult.default" title="Permalink to this definition">¶</a></dt>
<dd><p>A boolean indicating whether or not the VPC is the default one for the region.</p>
</dd></dl>

<dl class="py attribute">
<dt id="pulumi_digitalocean.GetVpcResult.description">
<code class="sig-name descname">description</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_digitalocean.GetVpcResult.description" title="Permalink to this definition">¶</a></dt>
<dd><p>A free-form text field describing the VPC.</p>
</dd></dl>

<dl class="py attribute">
<dt id="pulumi_digitalocean.GetVpcResult.id">
<code class="sig-name descname">id</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_digitalocean.GetVpcResult.id" title="Permalink to this definition">¶</a></dt>
<dd><p>The unique identifier for the VPC.</p>
</dd></dl>

<dl class="py attribute">
<dt id="pulumi_digitalocean.GetVpcResult.ip_range">
<code class="sig-name descname">ip_range</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_digitalocean.GetVpcResult.ip_range" title="Permalink to this definition">¶</a></dt>
<dd><p>The range of IP addresses for the VPC in CIDR notation.</p>
</dd></dl>

<dl class="py attribute">
<dt id="pulumi_digitalocean.GetVpcResult.name">
<code class="sig-name descname">name</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_digitalocean.GetVpcResult.name" title="Permalink to this definition">¶</a></dt>
<dd><p>The name of the VPC.</p>
</dd></dl>

<dl class="py attribute">
<dt id="pulumi_digitalocean.GetVpcResult.region">
<code class="sig-name descname">region</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_digitalocean.GetVpcResult.region" title="Permalink to this definition">¶</a></dt>
<dd><p>The DigitalOcean region slug for the VPC’s location.</p>
</dd></dl>

<dl class="py attribute">
<dt id="pulumi_digitalocean.GetVpcResult.urn">
<code class="sig-name descname">urn</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_digitalocean.GetVpcResult.urn" title="Permalink to this definition">¶</a></dt>
<dd><p>The uniform resource name (URN) for the VPC.</p>
</dd></dl>

</dd></dl>

<dl class="py class">
<dt id="pulumi_digitalocean.KubernetesCluster">
<em class="property">class </em><code class="sig-prename descclassname">pulumi_digitalocean.</code><code class="sig-name descname">KubernetesCluster</code><span class="sig-paren">(</span><em class="sig-param"><span class="n">resource_name</span></em>, <em class="sig-param"><span class="n">opts</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">name</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">node_pool</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">region</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">tags</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">version</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">vpc_uuid</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">__props__</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">__name__</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">__opts__</span><span class="o">=</span><span class="default_value">None</span></em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_digitalocean.KubernetesCluster" title="Permalink to this definition">¶</a></dt>
<dd><p>Provides a DigitalOcean Kubernetes cluster resource. This can be used to create, delete, and modify clusters. For more information see the <a class="reference external" href="https://www.digitalocean.com/docs/kubernetes/">official documentation</a>.</p>
<div class="highlight-python notranslate"><div class="highlight"><pre><span></span><span class="kn">import</span> <span class="nn">pulumi</span>
<span class="kn">import</span> <span class="nn">pulumi_digitalocean</span> <span class="k">as</span> <span class="nn">digitalocean</span>

<span class="n">foo</span> <span class="o">=</span> <span class="n">digitalocean</span><span class="o">.</span><span class="n">KubernetesCluster</span><span class="p">(</span><span class="s2">&quot;foo&quot;</span><span class="p">,</span>
    <span class="n">node_pool</span><span class="o">=</span><span class="p">{</span>
        <span class="s2">&quot;name&quot;</span><span class="p">:</span> <span class="s2">&quot;worker-pool&quot;</span><span class="p">,</span>
        <span class="s2">&quot;nodeCount&quot;</span><span class="p">:</span> <span class="mi">3</span><span class="p">,</span>
        <span class="s2">&quot;size&quot;</span><span class="p">:</span> <span class="s2">&quot;s-2vcpu-2gb&quot;</span><span class="p">,</span>
    <span class="p">},</span>
    <span class="n">region</span><span class="o">=</span><span class="s2">&quot;nyc1&quot;</span><span class="p">,</span>
    <span class="n">version</span><span class="o">=</span><span class="s2">&quot;1.15.5-do.1&quot;</span><span class="p">)</span>
</pre></div>
</div>
<div class="highlight-python notranslate"><div class="highlight"><pre><span></span><span class="kn">import</span> <span class="nn">pulumi</span>
<span class="kn">import</span> <span class="nn">pulumi_digitalocean</span> <span class="k">as</span> <span class="nn">digitalocean</span>

<span class="n">foo</span> <span class="o">=</span> <span class="n">digitalocean</span><span class="o">.</span><span class="n">KubernetesCluster</span><span class="p">(</span><span class="s2">&quot;foo&quot;</span><span class="p">,</span>
    <span class="n">node_pool</span><span class="o">=</span><span class="p">{</span>
        <span class="s2">&quot;autoScale&quot;</span><span class="p">:</span> <span class="kc">True</span><span class="p">,</span>
        <span class="s2">&quot;maxNodes&quot;</span><span class="p">:</span> <span class="mi">5</span><span class="p">,</span>
        <span class="s2">&quot;minNodes&quot;</span><span class="p">:</span> <span class="mi">1</span><span class="p">,</span>
        <span class="s2">&quot;name&quot;</span><span class="p">:</span> <span class="s2">&quot;autoscale-worker-pool&quot;</span><span class="p">,</span>
        <span class="s2">&quot;size&quot;</span><span class="p">:</span> <span class="s2">&quot;s-2vcpu-2gb&quot;</span><span class="p">,</span>
    <span class="p">},</span>
    <span class="n">region</span><span class="o">=</span><span class="s2">&quot;nyc1&quot;</span><span class="p">,</span>
    <span class="n">version</span><span class="o">=</span><span class="s2">&quot;1.15.5-do.1&quot;</span><span class="p">)</span>
</pre></div>
</div>
<dl class="field-list simple">
<dt class="field-odd">Parameters</dt>
<dd class="field-odd"><ul class="simple">
<li><p><strong>resource_name</strong> (<em>str</em>) – The name of the resource.</p></li>
<li><p><strong>opts</strong> (<a class="reference internal" href="../pulumi/#pulumi.ResourceOptions" title="pulumi.ResourceOptions"><em>pulumi.ResourceOptions</em></a>) – Options for the resource.</p></li>
<li><p><strong>name</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – A name for the Kubernetes cluster.</p></li>
<li><p><strong>node_pool</strong> (<em>pulumi.Input</em><em>[</em><em>dict</em><em>]</em>) – A block representing the cluster’s default node pool. Additional node pools may be added to the cluster using the <code class="docutils literal notranslate"><span class="pre">.KubernetesNodePool</span></code> resource. The following arguments may be specified:</p></li>
</ul>
</dd>
</dl>
<div class="highlight-default notranslate"><div class="highlight"><pre><span></span>- `name` - (Required) A name for the node pool.
- `size` - (Required) The slug identifier for the type of Droplet to be used as workers in the node pool.
- `node_count` - (Optional) The number of Droplet instances in the node pool. If auto-scaling is enabled, this should only be set if the desired result is to explicitly reset the number of nodes to this value. If auto-scaling is enabled, and the node count is outside of the given min/max range, it will use the min nodes value.
- `auto_scale` - (Optional) Enable auto-scaling of the number of nodes in the node pool within the given min/max range.
- `min_nodes` - (Optional) If auto-scaling is enabled, this represents the minimum number of nodes that the node pool can be scaled down to.
- `max_nodes` - (Optional) If auto-scaling is enabled, this represents the maximum number of nodes that the node pool can be scaled up to.
- `tags` - (Optional) A list of tag names to be applied to the Kubernetes cluster.
- `labels` - (Optional) A map of key/value pairs to apply to nodes in the pool. The labels are exposed in the Kubernetes API as labels in the metadata of the corresponding [Node resources](https://kubernetes.io/docs/concepts/architecture/nodes/).
</pre></div>
</div>
<dl class="field-list simple">
<dt class="field-odd">Parameters</dt>
<dd class="field-odd"><ul class="simple">
<li><p><strong>region</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – The slug identifier for the region where the Kubernetes cluster will be created.</p></li>
<li><p><strong>tags</strong> (<em>pulumi.Input</em><em>[</em><em>list</em><em>]</em>) – A list of tag names to be applied to the Kubernetes cluster.</p></li>
<li><p><strong>version</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – The slug identifier for the version of Kubernetes used for the cluster. Use <a class="reference external" href="https://github.com/digitalocean/doctl">doctl</a> to find the available versions <code class="docutils literal notranslate"><span class="pre">doctl</span> <span class="pre">kubernetes</span> <span class="pre">options</span> <span class="pre">versions</span></code>. (<strong>Note:</strong> A cluster may only be upgraded to newer versions in-place. If the version is decreased, a new resource will be created.)</p></li>
<li><p><strong>vpc_uuid</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – The ID of the VPC where the Kubernetes cluster will be located.</p></li>
</ul>
</dd>
</dl>
<p>The <strong>node_pool</strong> object supports the following:</p>
<ul class="simple">
<li><p><code class="docutils literal notranslate"><span class="pre">actual_node_count</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[float]</span></code>)</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">auto_scale</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[bool]</span></code>)</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">id</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[str]</span></code>) - A unique ID that can be used to identify and reference a Kubernetes cluster.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">labels</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[dict]</span></code>)</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">max_nodes</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[float]</span></code>)</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">min_nodes</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[float]</span></code>)</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">name</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[str]</span></code>) - A name for the Kubernetes cluster.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">node_count</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[float]</span></code>)</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">nodes</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[list]</span></code>)</p>
<ul>
<li><p><code class="docutils literal notranslate"><span class="pre">created_at</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[str]</span></code>) - The date and time when the Kubernetes cluster was created.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">droplet_id</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[str]</span></code>)</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">id</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[str]</span></code>) - A unique ID that can be used to identify and reference a Kubernetes cluster.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">name</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[str]</span></code>) - A name for the Kubernetes cluster.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">status</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[str]</span></code>) - A string indicating the current status of the cluster. Potential values include running, provisioning, and errored.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">updated_at</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[str]</span></code>) - The date and time when the Kubernetes cluster was last updated.</p>
<ul>
<li><p><code class="docutils literal notranslate"><span class="pre">kube_config.0</span></code> - A representation of the Kubernetes cluster’s kubeconfig with the following attributes:</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">raw_config</span></code> - The full contents of the Kubernetes cluster’s kubeconfig file.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">host</span></code> - The URL of the API server on the Kubernetes master node.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">cluster_ca_certificate</span></code> - The base64 encoded public certificate for the cluster’s certificate authority.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">token</span></code> - The DigitalOcean API access token used by clients to access the cluster.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">client_key</span></code> - The base64 encoded private key used by clients to access the cluster. Only available if token authentication is not supported on your cluster.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">client_certificate</span></code> - The base64 encoded public certificate used by clients to access the cluster. Only available if token authentication is not supported on your cluster.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">expires_at</span></code> - The date and time when the credentials will expire and need to be regenerated.</p></li>
</ul>
</li>
</ul>
</li>
<li><p><code class="docutils literal notranslate"><span class="pre">size</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[str]</span></code>)</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">tags</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[list]</span></code>) - A list of tag names to be applied to the Kubernetes cluster.</p></li>
</ul>
<dl class="py attribute">
<dt id="pulumi_digitalocean.KubernetesCluster.cluster_subnet">
<code class="sig-name descname">cluster_subnet</code><em class="property">: pulumi.Output[str]</em><em class="property"> = None</em><a class="headerlink" href="#pulumi_digitalocean.KubernetesCluster.cluster_subnet" title="Permalink to this definition">¶</a></dt>
<dd><p>The range of IP addresses in the overlay network of the Kubernetes cluster.</p>
</dd></dl>

<dl class="py attribute">
<dt id="pulumi_digitalocean.KubernetesCluster.created_at">
<code class="sig-name descname">created_at</code><em class="property">: pulumi.Output[str]</em><em class="property"> = None</em><a class="headerlink" href="#pulumi_digitalocean.KubernetesCluster.created_at" title="Permalink to this definition">¶</a></dt>
<dd><p>The date and time when the Kubernetes cluster was created.</p>
</dd></dl>

<dl class="py attribute">
<dt id="pulumi_digitalocean.KubernetesCluster.endpoint">
<code class="sig-name descname">endpoint</code><em class="property">: pulumi.Output[str]</em><em class="property"> = None</em><a class="headerlink" href="#pulumi_digitalocean.KubernetesCluster.endpoint" title="Permalink to this definition">¶</a></dt>
<dd><p>The base URL of the API server on the Kubernetes master node.</p>
</dd></dl>

<dl class="py attribute">
<dt id="pulumi_digitalocean.KubernetesCluster.ipv4_address">
<code class="sig-name descname">ipv4_address</code><em class="property">: pulumi.Output[str]</em><em class="property"> = None</em><a class="headerlink" href="#pulumi_digitalocean.KubernetesCluster.ipv4_address" title="Permalink to this definition">¶</a></dt>
<dd><p>The public IPv4 address of the Kubernetes master node.</p>
</dd></dl>

<dl class="py attribute">
<dt id="pulumi_digitalocean.KubernetesCluster.name">
<code class="sig-name descname">name</code><em class="property">: pulumi.Output[str]</em><em class="property"> = None</em><a class="headerlink" href="#pulumi_digitalocean.KubernetesCluster.name" title="Permalink to this definition">¶</a></dt>
<dd><p>A name for the Kubernetes cluster.</p>
</dd></dl>

<dl class="py attribute">
<dt id="pulumi_digitalocean.KubernetesCluster.node_pool">
<code class="sig-name descname">node_pool</code><em class="property">: pulumi.Output[dict]</em><em class="property"> = None</em><a class="headerlink" href="#pulumi_digitalocean.KubernetesCluster.node_pool" title="Permalink to this definition">¶</a></dt>
<dd><p>A block representing the cluster’s default node pool. Additional node pools may be added to the cluster using the <code class="docutils literal notranslate"><span class="pre">.KubernetesNodePool</span></code> resource. The following arguments may be specified:</p>
<ul class="simple">
<li><p><code class="docutils literal notranslate"><span class="pre">name</span></code> - (Required) A name for the node pool.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">size</span></code> - (Required) The slug identifier for the type of Droplet to be used as workers in the node pool.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">node_count</span></code> - (Optional) The number of Droplet instances in the node pool. If auto-scaling is enabled, this should only be set if the desired result is to explicitly reset the number of nodes to this value. If auto-scaling is enabled, and the node count is outside of the given min/max range, it will use the min nodes value.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">auto_scale</span></code> - (Optional) Enable auto-scaling of the number of nodes in the node pool within the given min/max range.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">min_nodes</span></code> - (Optional) If auto-scaling is enabled, this represents the minimum number of nodes that the node pool can be scaled down to.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">max_nodes</span></code> - (Optional) If auto-scaling is enabled, this represents the maximum number of nodes that the node pool can be scaled up to.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">tags</span></code> - (Optional) A list of tag names to be applied to the Kubernetes cluster.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">labels</span></code> - (Optional) A map of key/value pairs to apply to nodes in the pool. The labels are exposed in the Kubernetes API as labels in the metadata of the corresponding <a class="reference external" href="https://kubernetes.io/docs/concepts/architecture/nodes/">Node resources</a>.</p>
<ul>
<li><p><code class="docutils literal notranslate"><span class="pre">actual_node_count</span></code> (<code class="docutils literal notranslate"><span class="pre">float</span></code>)</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">auto_scale</span></code> (<code class="docutils literal notranslate"><span class="pre">bool</span></code>)</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">id</span></code> (<code class="docutils literal notranslate"><span class="pre">str</span></code>) - A unique ID that can be used to identify and reference a Kubernetes cluster.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">labels</span></code> (<code class="docutils literal notranslate"><span class="pre">dict</span></code>)</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">max_nodes</span></code> (<code class="docutils literal notranslate"><span class="pre">float</span></code>)</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">min_nodes</span></code> (<code class="docutils literal notranslate"><span class="pre">float</span></code>)</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">name</span></code> (<code class="docutils literal notranslate"><span class="pre">str</span></code>) - A name for the Kubernetes cluster.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">node_count</span></code> (<code class="docutils literal notranslate"><span class="pre">float</span></code>)</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">nodes</span></code> (<code class="docutils literal notranslate"><span class="pre">list</span></code>)</p>
<ul>
<li><p><code class="docutils literal notranslate"><span class="pre">created_at</span></code> (<code class="docutils literal notranslate"><span class="pre">str</span></code>) - The date and time when the Kubernetes cluster was created.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">droplet_id</span></code> (<code class="docutils literal notranslate"><span class="pre">str</span></code>)</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">id</span></code> (<code class="docutils literal notranslate"><span class="pre">str</span></code>) - A unique ID that can be used to identify and reference a Kubernetes cluster.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">name</span></code> (<code class="docutils literal notranslate"><span class="pre">str</span></code>) - A name for the Kubernetes cluster.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">status</span></code> (<code class="docutils literal notranslate"><span class="pre">str</span></code>) - A string indicating the current status of the cluster. Potential values include running, provisioning, and errored.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">updated_at</span></code> (<code class="docutils literal notranslate"><span class="pre">str</span></code>) - The date and time when the Kubernetes cluster was last updated.</p>
<ul>
<li><p><code class="docutils literal notranslate"><span class="pre">kube_config.0</span></code> - A representation of the Kubernetes cluster’s kubeconfig with the following attributes:</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">raw_config</span></code> - The full contents of the Kubernetes cluster’s kubeconfig file.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">host</span></code> - The URL of the API server on the Kubernetes master node.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">cluster_ca_certificate</span></code> - The base64 encoded public certificate for the cluster’s certificate authority.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">token</span></code> - The DigitalOcean API access token used by clients to access the cluster.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">client_key</span></code> - The base64 encoded private key used by clients to access the cluster. Only available if token authentication is not supported on your cluster.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">client_certificate</span></code> - The base64 encoded public certificate used by clients to access the cluster. Only available if token authentication is not supported on your cluster.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">expires_at</span></code> - The date and time when the credentials will expire and need to be regenerated.</p></li>
</ul>
</li>
</ul>
</li>
<li><p><code class="docutils literal notranslate"><span class="pre">size</span></code> (<code class="docutils literal notranslate"><span class="pre">str</span></code>)</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">tags</span></code> (<code class="docutils literal notranslate"><span class="pre">list</span></code>) - A list of tag names to be applied to the Kubernetes cluster.</p></li>
</ul>
</li>
</ul>
</dd></dl>

<dl class="py attribute">
<dt id="pulumi_digitalocean.KubernetesCluster.region">
<code class="sig-name descname">region</code><em class="property">: pulumi.Output[str]</em><em class="property"> = None</em><a class="headerlink" href="#pulumi_digitalocean.KubernetesCluster.region" title="Permalink to this definition">¶</a></dt>
<dd><p>The slug identifier for the region where the Kubernetes cluster will be created.</p>
</dd></dl>

<dl class="py attribute">
<dt id="pulumi_digitalocean.KubernetesCluster.service_subnet">
<code class="sig-name descname">service_subnet</code><em class="property">: pulumi.Output[str]</em><em class="property"> = None</em><a class="headerlink" href="#pulumi_digitalocean.KubernetesCluster.service_subnet" title="Permalink to this definition">¶</a></dt>
<dd><p>The range of assignable IP addresses for services running in the Kubernetes cluster.</p>
</dd></dl>

<dl class="py attribute">
<dt id="pulumi_digitalocean.KubernetesCluster.status">
<code class="sig-name descname">status</code><em class="property">: pulumi.Output[str]</em><em class="property"> = None</em><a class="headerlink" href="#pulumi_digitalocean.KubernetesCluster.status" title="Permalink to this definition">¶</a></dt>
<dd><p>A string indicating the current status of the cluster. Potential values include running, provisioning, and errored.</p>
</dd></dl>

<dl class="py attribute">
<dt id="pulumi_digitalocean.KubernetesCluster.tags">
<code class="sig-name descname">tags</code><em class="property">: pulumi.Output[list]</em><em class="property"> = None</em><a class="headerlink" href="#pulumi_digitalocean.KubernetesCluster.tags" title="Permalink to this definition">¶</a></dt>
<dd><p>A list of tag names to be applied to the Kubernetes cluster.</p>
</dd></dl>

<dl class="py attribute">
<dt id="pulumi_digitalocean.KubernetesCluster.updated_at">
<code class="sig-name descname">updated_at</code><em class="property">: pulumi.Output[str]</em><em class="property"> = None</em><a class="headerlink" href="#pulumi_digitalocean.KubernetesCluster.updated_at" title="Permalink to this definition">¶</a></dt>
<dd><p>The date and time when the Kubernetes cluster was last updated.</p>
<ul class="simple">
<li><p><code class="docutils literal notranslate"><span class="pre">kube_config.0</span></code> - A representation of the Kubernetes cluster’s kubeconfig with the following attributes:</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">raw_config</span></code> - The full contents of the Kubernetes cluster’s kubeconfig file.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">host</span></code> - The URL of the API server on the Kubernetes master node.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">cluster_ca_certificate</span></code> - The base64 encoded public certificate for the cluster’s certificate authority.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">token</span></code> - The DigitalOcean API access token used by clients to access the cluster.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">client_key</span></code> - The base64 encoded private key used by clients to access the cluster. Only available if token authentication is not supported on your cluster.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">client_certificate</span></code> - The base64 encoded public certificate used by clients to access the cluster. Only available if token authentication is not supported on your cluster.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">expires_at</span></code> - The date and time when the credentials will expire and need to be regenerated.</p></li>
</ul>
</dd></dl>

<dl class="py attribute">
<dt id="pulumi_digitalocean.KubernetesCluster.version">
<code class="sig-name descname">version</code><em class="property">: pulumi.Output[str]</em><em class="property"> = None</em><a class="headerlink" href="#pulumi_digitalocean.KubernetesCluster.version" title="Permalink to this definition">¶</a></dt>
<dd><p>The slug identifier for the version of Kubernetes used for the cluster. Use <a class="reference external" href="https://github.com/digitalocean/doctl">doctl</a> to find the available versions <code class="docutils literal notranslate"><span class="pre">doctl</span> <span class="pre">kubernetes</span> <span class="pre">options</span> <span class="pre">versions</span></code>. (<strong>Note:</strong> A cluster may only be upgraded to newer versions in-place. If the version is decreased, a new resource will be created.)</p>
</dd></dl>

<dl class="py attribute">
<dt id="pulumi_digitalocean.KubernetesCluster.vpc_uuid">
<code class="sig-name descname">vpc_uuid</code><em class="property">: pulumi.Output[str]</em><em class="property"> = None</em><a class="headerlink" href="#pulumi_digitalocean.KubernetesCluster.vpc_uuid" title="Permalink to this definition">¶</a></dt>
<dd><p>The ID of the VPC where the Kubernetes cluster will be located.</p>
</dd></dl>

<dl class="py method">
<dt id="pulumi_digitalocean.KubernetesCluster.get">
<em class="property">static </em><code class="sig-name descname">get</code><span class="sig-paren">(</span><em class="sig-param"><span class="n">resource_name</span></em>, <em class="sig-param"><span class="n">id</span></em>, <em class="sig-param"><span class="n">opts</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">cluster_subnet</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">created_at</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">endpoint</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">ipv4_address</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">kube_configs</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">name</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">node_pool</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">region</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">service_subnet</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">status</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">tags</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">updated_at</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">version</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">vpc_uuid</span><span class="o">=</span><span class="default_value">None</span></em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_digitalocean.KubernetesCluster.get" title="Permalink to this definition">¶</a></dt>
<dd><p>Get an existing KubernetesCluster resource’s state with the given name, id, and optional extra
properties used to qualify the lookup.</p>
<dl class="field-list simple">
<dt class="field-odd">Parameters</dt>
<dd class="field-odd"><ul class="simple">
<li><p><strong>resource_name</strong> (<em>str</em>) – The unique name of the resulting resource.</p></li>
<li><p><strong>id</strong> (<em>str</em>) – The unique provider ID of the resource to lookup.</p></li>
<li><p><strong>opts</strong> (<a class="reference internal" href="../pulumi/#pulumi.ResourceOptions" title="pulumi.ResourceOptions"><em>pulumi.ResourceOptions</em></a>) – Options for the resource.</p></li>
<li><p><strong>cluster_subnet</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – The range of IP addresses in the overlay network of the Kubernetes cluster.</p></li>
<li><p><strong>created_at</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – The date and time when the Kubernetes cluster was created.</p></li>
<li><p><strong>endpoint</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – The base URL of the API server on the Kubernetes master node.</p></li>
<li><p><strong>ipv4_address</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – The public IPv4 address of the Kubernetes master node.</p></li>
<li><p><strong>name</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – A name for the Kubernetes cluster.</p></li>
<li><p><strong>node_pool</strong> (<em>pulumi.Input</em><em>[</em><em>dict</em><em>]</em>) – A block representing the cluster’s default node pool. Additional node pools may be added to the cluster using the <code class="docutils literal notranslate"><span class="pre">.KubernetesNodePool</span></code> resource. The following arguments may be specified:</p></li>
</ul>
</dd>
</dl>
<div class="highlight-default notranslate"><div class="highlight"><pre><span></span>- `name` - (Required) A name for the node pool.
- `size` - (Required) The slug identifier for the type of Droplet to be used as workers in the node pool.
- `node_count` - (Optional) The number of Droplet instances in the node pool. If auto-scaling is enabled, this should only be set if the desired result is to explicitly reset the number of nodes to this value. If auto-scaling is enabled, and the node count is outside of the given min/max range, it will use the min nodes value.
- `auto_scale` - (Optional) Enable auto-scaling of the number of nodes in the node pool within the given min/max range.
- `min_nodes` - (Optional) If auto-scaling is enabled, this represents the minimum number of nodes that the node pool can be scaled down to.
- `max_nodes` - (Optional) If auto-scaling is enabled, this represents the maximum number of nodes that the node pool can be scaled up to.
- `tags` - (Optional) A list of tag names to be applied to the Kubernetes cluster.
- `labels` - (Optional) A map of key/value pairs to apply to nodes in the pool. The labels are exposed in the Kubernetes API as labels in the metadata of the corresponding [Node resources](https://kubernetes.io/docs/concepts/architecture/nodes/).
</pre></div>
</div>
<dl class="field-list simple">
<dt class="field-odd">Parameters</dt>
<dd class="field-odd"><ul class="simple">
<li><p><strong>region</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – The slug identifier for the region where the Kubernetes cluster will be created.</p></li>
<li><p><strong>service_subnet</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – The range of assignable IP addresses for services running in the Kubernetes cluster.</p></li>
<li><p><strong>status</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – A string indicating the current status of the cluster. Potential values include running, provisioning, and errored.</p></li>
<li><p><strong>tags</strong> (<em>pulumi.Input</em><em>[</em><em>list</em><em>]</em>) – A list of tag names to be applied to the Kubernetes cluster.</p></li>
<li><p><strong>updated_at</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – The date and time when the Kubernetes cluster was last updated.</p></li>
</ul>
</dd>
</dl>
<div class="highlight-default notranslate"><div class="highlight"><pre><span></span>* `kube_config.0` - A representation of the Kubernetes cluster&#39;s kubeconfig with the following attributes:
- `raw_config` - The full contents of the Kubernetes cluster&#39;s kubeconfig file.
- `host` - The URL of the API server on the Kubernetes master node.
- `cluster_ca_certificate` - The base64 encoded public certificate for the cluster&#39;s certificate authority.
- `token` - The DigitalOcean API access token used by clients to access the cluster.
- `client_key` - The base64 encoded private key used by clients to access the cluster. Only available if token authentication is not supported on your cluster.
- `client_certificate` - The base64 encoded public certificate used by clients to access the cluster. Only available if token authentication is not supported on your cluster.
- `expires_at` - The date and time when the credentials will expire and need to be regenerated.
</pre></div>
</div>
<dl class="field-list simple">
<dt class="field-odd">Parameters</dt>
<dd class="field-odd"><ul class="simple">
<li><p><strong>version</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – <p>The slug identifier for the version of Kubernetes used for the cluster. Use <a class="reference external" href="https://github.com/digitalocean/doctl">doctl</a> to find the available versions <code class="docutils literal notranslate"><span class="pre">doctl</span> <span class="pre">kubernetes</span> <span class="pre">options</span> <span class="pre">versions</span></code>. (<strong>Note:</strong> A cluster may only be upgraded to newer versions in-place. If the version is decreased, a new resource will be created.)</p>
</p></li>
<li><p><strong>vpc_uuid</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – The ID of the VPC where the Kubernetes cluster will be located.</p></li>
</ul>
</dd>
</dl>
<p>The <strong>kube_configs</strong> object supports the following:</p>
<ul class="simple">
<li><p><code class="docutils literal notranslate"><span class="pre">clientCertificate</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[str]</span></code>)</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">clientKey</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[str]</span></code>)</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">clusterCaCertificate</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[str]</span></code>)</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">expiresAt</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[str]</span></code>)</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">host</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[str]</span></code>)</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">rawConfig</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[str]</span></code>)</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">token</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[str]</span></code>)</p></li>
</ul>
<p>The <strong>node_pool</strong> object supports the following:</p>
<ul class="simple">
<li><p><code class="docutils literal notranslate"><span class="pre">actual_node_count</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[float]</span></code>)</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">auto_scale</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[bool]</span></code>)</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">id</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[str]</span></code>) - A unique ID that can be used to identify and reference a Kubernetes cluster.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">labels</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[dict]</span></code>)</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">max_nodes</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[float]</span></code>)</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">min_nodes</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[float]</span></code>)</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">name</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[str]</span></code>) - A name for the Kubernetes cluster.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">node_count</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[float]</span></code>)</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">nodes</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[list]</span></code>)</p>
<ul>
<li><p><code class="docutils literal notranslate"><span class="pre">created_at</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[str]</span></code>) - The date and time when the Kubernetes cluster was created.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">droplet_id</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[str]</span></code>)</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">id</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[str]</span></code>) - A unique ID that can be used to identify and reference a Kubernetes cluster.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">name</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[str]</span></code>) - A name for the Kubernetes cluster.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">status</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[str]</span></code>) - A string indicating the current status of the cluster. Potential values include running, provisioning, and errored.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">updated_at</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[str]</span></code>) - The date and time when the Kubernetes cluster was last updated.</p>
<ul>
<li><p><code class="docutils literal notranslate"><span class="pre">kube_config.0</span></code> - A representation of the Kubernetes cluster’s kubeconfig with the following attributes:</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">raw_config</span></code> - The full contents of the Kubernetes cluster’s kubeconfig file.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">host</span></code> - The URL of the API server on the Kubernetes master node.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">cluster_ca_certificate</span></code> - The base64 encoded public certificate for the cluster’s certificate authority.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">token</span></code> - The DigitalOcean API access token used by clients to access the cluster.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">client_key</span></code> - The base64 encoded private key used by clients to access the cluster. Only available if token authentication is not supported on your cluster.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">client_certificate</span></code> - The base64 encoded public certificate used by clients to access the cluster. Only available if token authentication is not supported on your cluster.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">expires_at</span></code> - The date and time when the credentials will expire and need to be regenerated.</p></li>
</ul>
</li>
</ul>
</li>
<li><p><code class="docutils literal notranslate"><span class="pre">size</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[str]</span></code>)</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">tags</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[list]</span></code>) - A list of tag names to be applied to the Kubernetes cluster.</p></li>
</ul>
</dd></dl>

<dl class="py method">
<dt id="pulumi_digitalocean.KubernetesCluster.translate_output_property">
<code class="sig-name descname">translate_output_property</code><span class="sig-paren">(</span><em class="sig-param"><span class="n">prop</span></em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_digitalocean.KubernetesCluster.translate_output_property" title="Permalink to this definition">¶</a></dt>
<dd><p>Provides subclasses of Resource an opportunity to translate names of output properties
into a format of their choosing before writing those properties to the resource object.</p>
<dl class="field-list simple">
<dt class="field-odd">Parameters</dt>
<dd class="field-odd"><p><strong>prop</strong> (<em>str</em>) – A property name.</p>
</dd>
<dt class="field-even">Returns</dt>
<dd class="field-even"><p>A potentially transformed property name.</p>
</dd>
<dt class="field-odd">Return type</dt>
<dd class="field-odd"><p>str</p>
</dd>
</dl>
</dd></dl>

<dl class="py method">
<dt id="pulumi_digitalocean.KubernetesCluster.translate_input_property">
<code class="sig-name descname">translate_input_property</code><span class="sig-paren">(</span><em class="sig-param"><span class="n">prop</span></em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_digitalocean.KubernetesCluster.translate_input_property" title="Permalink to this definition">¶</a></dt>
<dd><p>Provides subclasses of Resource an opportunity to translate names of input properties into
a format of their choosing before sending those properties to the Pulumi engine.</p>
<dl class="field-list simple">
<dt class="field-odd">Parameters</dt>
<dd class="field-odd"><p><strong>prop</strong> (<em>str</em>) – A property name.</p>
</dd>
<dt class="field-even">Returns</dt>
<dd class="field-even"><p>A potentially transformed property name.</p>
</dd>
<dt class="field-odd">Return type</dt>
<dd class="field-odd"><p>str</p>
</dd>
</dl>
</dd></dl>

</dd></dl>

<dl class="py class">
<dt id="pulumi_digitalocean.KubernetesNodePool">
<em class="property">class </em><code class="sig-prename descclassname">pulumi_digitalocean.</code><code class="sig-name descname">KubernetesNodePool</code><span class="sig-paren">(</span><em class="sig-param"><span class="n">resource_name</span></em>, <em class="sig-param"><span class="n">opts</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">auto_scale</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">cluster_id</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">labels</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">max_nodes</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">min_nodes</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">name</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">node_count</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">size</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">tags</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">__props__</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">__name__</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">__opts__</span><span class="o">=</span><span class="default_value">None</span></em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_digitalocean.KubernetesNodePool" title="Permalink to this definition">¶</a></dt>
<dd><p>Provides a DigitalOcean Kubernetes node pool resource. While the default node pool must be defined in the <code class="docutils literal notranslate"><span class="pre">.KubernetesCluster</span></code> resource, this resource can be used to add additional ones to a cluster.</p>
<div class="highlight-python notranslate"><div class="highlight"><pre><span></span><span class="kn">import</span> <span class="nn">pulumi</span>
<span class="kn">import</span> <span class="nn">pulumi_digitalocean</span> <span class="k">as</span> <span class="nn">digitalocean</span>

<span class="n">foo</span> <span class="o">=</span> <span class="n">digitalocean</span><span class="o">.</span><span class="n">KubernetesCluster</span><span class="p">(</span><span class="s2">&quot;foo&quot;</span><span class="p">,</span>
    <span class="n">region</span><span class="o">=</span><span class="s2">&quot;nyc1&quot;</span><span class="p">,</span>
    <span class="n">version</span><span class="o">=</span><span class="s2">&quot;1.15.5-do.1&quot;</span><span class="p">,</span>
    <span class="n">node_pool</span><span class="o">=</span><span class="p">{</span>
        <span class="s2">&quot;name&quot;</span><span class="p">:</span> <span class="s2">&quot;front-end-pool&quot;</span><span class="p">,</span>
        <span class="s2">&quot;size&quot;</span><span class="p">:</span> <span class="s2">&quot;s-2vcpu-2gb&quot;</span><span class="p">,</span>
        <span class="s2">&quot;nodeCount&quot;</span><span class="p">:</span> <span class="mi">3</span><span class="p">,</span>
    <span class="p">})</span>
<span class="n">bar</span> <span class="o">=</span> <span class="n">digitalocean</span><span class="o">.</span><span class="n">KubernetesNodePool</span><span class="p">(</span><span class="s2">&quot;bar&quot;</span><span class="p">,</span>
    <span class="n">cluster_id</span><span class="o">=</span><span class="n">foo</span><span class="o">.</span><span class="n">id</span><span class="p">,</span>
    <span class="n">size</span><span class="o">=</span><span class="s2">&quot;c-2&quot;</span><span class="p">,</span>
    <span class="n">node_count</span><span class="o">=</span><span class="mi">2</span><span class="p">,</span>
    <span class="n">tags</span><span class="o">=</span><span class="p">[</span><span class="s2">&quot;backend&quot;</span><span class="p">],</span>
    <span class="n">labels</span><span class="o">=</span><span class="p">{</span>
        <span class="s2">&quot;service&quot;</span><span class="p">:</span> <span class="s2">&quot;backend&quot;</span><span class="p">,</span>
        <span class="s2">&quot;priority&quot;</span><span class="p">:</span> <span class="s2">&quot;high&quot;</span><span class="p">,</span>
    <span class="p">})</span>
</pre></div>
</div>
<div class="highlight-python notranslate"><div class="highlight"><pre><span></span><span class="kn">import</span> <span class="nn">pulumi</span>
<span class="kn">import</span> <span class="nn">pulumi_digitalocean</span> <span class="k">as</span> <span class="nn">digitalocean</span>

<span class="n">autoscale_pool_01</span> <span class="o">=</span> <span class="n">digitalocean</span><span class="o">.</span><span class="n">KubernetesNodePool</span><span class="p">(</span><span class="s2">&quot;autoscale-pool-01&quot;</span><span class="p">,</span>
    <span class="n">cluster_id</span><span class="o">=</span><span class="n">digitalocean_kubernetes_cluster</span><span class="p">[</span><span class="s2">&quot;foo&quot;</span><span class="p">][</span><span class="s2">&quot;id&quot;</span><span class="p">],</span>
    <span class="n">size</span><span class="o">=</span><span class="s2">&quot;s-1vcpu-2gb&quot;</span><span class="p">,</span>
    <span class="n">auto_scale</span><span class="o">=</span><span class="kc">True</span><span class="p">,</span>
    <span class="n">min_nodes</span><span class="o">=</span><span class="mi">0</span><span class="p">,</span>
    <span class="n">max_nodes</span><span class="o">=</span><span class="mi">5</span><span class="p">)</span>
</pre></div>
</div>
<dl class="field-list simple">
<dt class="field-odd">Parameters</dt>
<dd class="field-odd"><ul class="simple">
<li><p><strong>resource_name</strong> (<em>str</em>) – The name of the resource.</p></li>
<li><p><strong>opts</strong> (<a class="reference internal" href="../pulumi/#pulumi.ResourceOptions" title="pulumi.ResourceOptions"><em>pulumi.ResourceOptions</em></a>) – Options for the resource.</p></li>
<li><p><strong>auto_scale</strong> (<em>pulumi.Input</em><em>[</em><em>bool</em><em>]</em>) – Enable auto-scaling of the number of nodes in the node pool within the given min/max range.</p></li>
<li><p><strong>cluster_id</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – The ID of the Kubernetes cluster to which the node pool is associated.</p></li>
<li><p><strong>labels</strong> (<em>pulumi.Input</em><em>[</em><em>dict</em><em>]</em>) – <p>A map of key/value pairs to apply to nodes in the pool. The labels are exposed in the Kubernetes API as labels in the metadata of the corresponding <a class="reference external" href="https://kubernetes.io/docs/concepts/architecture/nodes/">Node resources</a>.</p>
</p></li>
<li><p><strong>max_nodes</strong> (<em>pulumi.Input</em><em>[</em><em>float</em><em>]</em>) – If auto-scaling is enabled, this represents the maximum number of nodes that the node pool can be scaled up to.</p></li>
<li><p><strong>min_nodes</strong> (<em>pulumi.Input</em><em>[</em><em>float</em><em>]</em>) – If auto-scaling is enabled, this represents the minimum number of nodes that the node pool can be scaled down to.</p></li>
<li><p><strong>name</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – A name for the node pool.</p></li>
<li><p><strong>node_count</strong> (<em>pulumi.Input</em><em>[</em><em>float</em><em>]</em>) – The number of Droplet instances in the node pool. If auto-scaling is enabled, this should only be set if the desired result is to explicitly reset the number of nodes to this value. If auto-scaling is enabled, and the node count is outside of the given min/max range, it will use the min nodes value.</p></li>
<li><p><strong>size</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – The slug identifier for the type of Droplet to be used as workers in the node pool.</p></li>
<li><p><strong>tags</strong> (<em>pulumi.Input</em><em>[</em><em>list</em><em>]</em>) – A list of tag names to be applied to the Kubernetes cluster.</p></li>
</ul>
</dd>
</dl>
<dl class="py attribute">
<dt id="pulumi_digitalocean.KubernetesNodePool.actual_node_count">
<code class="sig-name descname">actual_node_count</code><em class="property">: pulumi.Output[float]</em><em class="property"> = None</em><a class="headerlink" href="#pulumi_digitalocean.KubernetesNodePool.actual_node_count" title="Permalink to this definition">¶</a></dt>
<dd><p>A computed field representing the actual number of nodes in the node pool, which is especially useful when auto-scaling is enabled.</p>
</dd></dl>

<dl class="py attribute">
<dt id="pulumi_digitalocean.KubernetesNodePool.auto_scale">
<code class="sig-name descname">auto_scale</code><em class="property">: pulumi.Output[bool]</em><em class="property"> = None</em><a class="headerlink" href="#pulumi_digitalocean.KubernetesNodePool.auto_scale" title="Permalink to this definition">¶</a></dt>
<dd><p>Enable auto-scaling of the number of nodes in the node pool within the given min/max range.</p>
</dd></dl>

<dl class="py attribute">
<dt id="pulumi_digitalocean.KubernetesNodePool.cluster_id">
<code class="sig-name descname">cluster_id</code><em class="property">: pulumi.Output[str]</em><em class="property"> = None</em><a class="headerlink" href="#pulumi_digitalocean.KubernetesNodePool.cluster_id" title="Permalink to this definition">¶</a></dt>
<dd><p>The ID of the Kubernetes cluster to which the node pool is associated.</p>
</dd></dl>

<dl class="py attribute">
<dt id="pulumi_digitalocean.KubernetesNodePool.labels">
<code class="sig-name descname">labels</code><em class="property">: pulumi.Output[dict]</em><em class="property"> = None</em><a class="headerlink" href="#pulumi_digitalocean.KubernetesNodePool.labels" title="Permalink to this definition">¶</a></dt>
<dd><p>A map of key/value pairs to apply to nodes in the pool. The labels are exposed in the Kubernetes API as labels in the metadata of the corresponding <a class="reference external" href="https://kubernetes.io/docs/concepts/architecture/nodes/">Node resources</a>.</p>
</dd></dl>

<dl class="py attribute">
<dt id="pulumi_digitalocean.KubernetesNodePool.max_nodes">
<code class="sig-name descname">max_nodes</code><em class="property">: pulumi.Output[float]</em><em class="property"> = None</em><a class="headerlink" href="#pulumi_digitalocean.KubernetesNodePool.max_nodes" title="Permalink to this definition">¶</a></dt>
<dd><p>If auto-scaling is enabled, this represents the maximum number of nodes that the node pool can be scaled up to.</p>
</dd></dl>

<dl class="py attribute">
<dt id="pulumi_digitalocean.KubernetesNodePool.min_nodes">
<code class="sig-name descname">min_nodes</code><em class="property">: pulumi.Output[float]</em><em class="property"> = None</em><a class="headerlink" href="#pulumi_digitalocean.KubernetesNodePool.min_nodes" title="Permalink to this definition">¶</a></dt>
<dd><p>If auto-scaling is enabled, this represents the minimum number of nodes that the node pool can be scaled down to.</p>
</dd></dl>

<dl class="py attribute">
<dt id="pulumi_digitalocean.KubernetesNodePool.name">
<code class="sig-name descname">name</code><em class="property">: pulumi.Output[str]</em><em class="property"> = None</em><a class="headerlink" href="#pulumi_digitalocean.KubernetesNodePool.name" title="Permalink to this definition">¶</a></dt>
<dd><p>A name for the node pool.</p>
</dd></dl>

<dl class="py attribute">
<dt id="pulumi_digitalocean.KubernetesNodePool.node_count">
<code class="sig-name descname">node_count</code><em class="property">: pulumi.Output[float]</em><em class="property"> = None</em><a class="headerlink" href="#pulumi_digitalocean.KubernetesNodePool.node_count" title="Permalink to this definition">¶</a></dt>
<dd><p>The number of Droplet instances in the node pool. If auto-scaling is enabled, this should only be set if the desired result is to explicitly reset the number of nodes to this value. If auto-scaling is enabled, and the node count is outside of the given min/max range, it will use the min nodes value.</p>
</dd></dl>

<dl class="py attribute">
<dt id="pulumi_digitalocean.KubernetesNodePool.nodes">
<code class="sig-name descname">nodes</code><em class="property">: pulumi.Output[list]</em><em class="property"> = None</em><a class="headerlink" href="#pulumi_digitalocean.KubernetesNodePool.nodes" title="Permalink to this definition">¶</a></dt>
<dd><p>A list of nodes in the pool. Each node exports the following attributes:</p>
<ul class="simple">
<li><p><code class="docutils literal notranslate"><span class="pre">id</span></code> -  A unique ID that can be used to identify and reference the node.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">name</span></code> - The auto-generated name for the node.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">status</span></code> -  A string indicating the current status of the individual node.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">droplet_id</span></code> - The id of the node’s droplet</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">created_at</span></code> - The date and time when the node was created.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">updated_at</span></code> - The date and time when the node was last updated.</p>
<ul>
<li><p><code class="docutils literal notranslate"><span class="pre">created_at</span></code> (<code class="docutils literal notranslate"><span class="pre">str</span></code>)</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">droplet_id</span></code> (<code class="docutils literal notranslate"><span class="pre">str</span></code>)</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">id</span></code> (<code class="docutils literal notranslate"><span class="pre">str</span></code>) - A unique ID that can be used to identify and reference the node pool.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">name</span></code> (<code class="docutils literal notranslate"><span class="pre">str</span></code>) - A name for the node pool.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">status</span></code> (<code class="docutils literal notranslate"><span class="pre">str</span></code>)</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">updated_at</span></code> (<code class="docutils literal notranslate"><span class="pre">str</span></code>)</p></li>
</ul>
</li>
</ul>
</dd></dl>

<dl class="py attribute">
<dt id="pulumi_digitalocean.KubernetesNodePool.size">
<code class="sig-name descname">size</code><em class="property">: pulumi.Output[str]</em><em class="property"> = None</em><a class="headerlink" href="#pulumi_digitalocean.KubernetesNodePool.size" title="Permalink to this definition">¶</a></dt>
<dd><p>The slug identifier for the type of Droplet to be used as workers in the node pool.</p>
</dd></dl>

<dl class="py attribute">
<dt id="pulumi_digitalocean.KubernetesNodePool.tags">
<code class="sig-name descname">tags</code><em class="property">: pulumi.Output[list]</em><em class="property"> = None</em><a class="headerlink" href="#pulumi_digitalocean.KubernetesNodePool.tags" title="Permalink to this definition">¶</a></dt>
<dd><p>A list of tag names to be applied to the Kubernetes cluster.</p>
</dd></dl>

<dl class="py method">
<dt id="pulumi_digitalocean.KubernetesNodePool.get">
<em class="property">static </em><code class="sig-name descname">get</code><span class="sig-paren">(</span><em class="sig-param"><span class="n">resource_name</span></em>, <em class="sig-param"><span class="n">id</span></em>, <em class="sig-param"><span class="n">opts</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">actual_node_count</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">auto_scale</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">cluster_id</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">labels</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">max_nodes</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">min_nodes</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">name</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">node_count</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">nodes</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">size</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">tags</span><span class="o">=</span><span class="default_value">None</span></em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_digitalocean.KubernetesNodePool.get" title="Permalink to this definition">¶</a></dt>
<dd><p>Get an existing KubernetesNodePool resource’s state with the given name, id, and optional extra
properties used to qualify the lookup.</p>
<dl class="field-list simple">
<dt class="field-odd">Parameters</dt>
<dd class="field-odd"><ul class="simple">
<li><p><strong>resource_name</strong> (<em>str</em>) – The unique name of the resulting resource.</p></li>
<li><p><strong>id</strong> (<em>str</em>) – The unique provider ID of the resource to lookup.</p></li>
<li><p><strong>opts</strong> (<a class="reference internal" href="../pulumi/#pulumi.ResourceOptions" title="pulumi.ResourceOptions"><em>pulumi.ResourceOptions</em></a>) – Options for the resource.</p></li>
<li><p><strong>actual_node_count</strong> (<em>pulumi.Input</em><em>[</em><em>float</em><em>]</em>) – A computed field representing the actual number of nodes in the node pool, which is especially useful when auto-scaling is enabled.</p></li>
<li><p><strong>auto_scale</strong> (<em>pulumi.Input</em><em>[</em><em>bool</em><em>]</em>) – Enable auto-scaling of the number of nodes in the node pool within the given min/max range.</p></li>
<li><p><strong>cluster_id</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – The ID of the Kubernetes cluster to which the node pool is associated.</p></li>
<li><p><strong>labels</strong> (<em>pulumi.Input</em><em>[</em><em>dict</em><em>]</em>) – <p>A map of key/value pairs to apply to nodes in the pool. The labels are exposed in the Kubernetes API as labels in the metadata of the corresponding <a class="reference external" href="https://kubernetes.io/docs/concepts/architecture/nodes/">Node resources</a>.</p>
</p></li>
<li><p><strong>max_nodes</strong> (<em>pulumi.Input</em><em>[</em><em>float</em><em>]</em>) – If auto-scaling is enabled, this represents the maximum number of nodes that the node pool can be scaled up to.</p></li>
<li><p><strong>min_nodes</strong> (<em>pulumi.Input</em><em>[</em><em>float</em><em>]</em>) – If auto-scaling is enabled, this represents the minimum number of nodes that the node pool can be scaled down to.</p></li>
<li><p><strong>name</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – A name for the node pool.</p></li>
<li><p><strong>node_count</strong> (<em>pulumi.Input</em><em>[</em><em>float</em><em>]</em>) – The number of Droplet instances in the node pool. If auto-scaling is enabled, this should only be set if the desired result is to explicitly reset the number of nodes to this value. If auto-scaling is enabled, and the node count is outside of the given min/max range, it will use the min nodes value.</p></li>
<li><p><strong>nodes</strong> (<em>pulumi.Input</em><em>[</em><em>list</em><em>]</em>) – A list of nodes in the pool. Each node exports the following attributes:</p></li>
</ul>
</dd>
</dl>
<div class="highlight-default notranslate"><div class="highlight"><pre><span></span>- `id` -  A unique ID that can be used to identify and reference the node.
- `name` - The auto-generated name for the node.
- `status` -  A string indicating the current status of the individual node.
- `droplet_id` - The id of the node&#39;s droplet
- `created_at` - The date and time when the node was created.
- `updated_at` - The date and time when the node was last updated.
</pre></div>
</div>
<dl class="field-list simple">
<dt class="field-odd">Parameters</dt>
<dd class="field-odd"><ul class="simple">
<li><p><strong>size</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – The slug identifier for the type of Droplet to be used as workers in the node pool.</p></li>
<li><p><strong>tags</strong> (<em>pulumi.Input</em><em>[</em><em>list</em><em>]</em>) – A list of tag names to be applied to the Kubernetes cluster.</p></li>
</ul>
</dd>
</dl>
<p>The <strong>nodes</strong> object supports the following:</p>
<ul class="simple">
<li><p><code class="docutils literal notranslate"><span class="pre">created_at</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[str]</span></code>)</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">droplet_id</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[str]</span></code>)</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">id</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[str]</span></code>) - A unique ID that can be used to identify and reference the node pool.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">name</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[str]</span></code>) - A name for the node pool.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">status</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[str]</span></code>)</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">updated_at</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[str]</span></code>)</p></li>
</ul>
</dd></dl>

<dl class="py method">
<dt id="pulumi_digitalocean.KubernetesNodePool.translate_output_property">
<code class="sig-name descname">translate_output_property</code><span class="sig-paren">(</span><em class="sig-param"><span class="n">prop</span></em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_digitalocean.KubernetesNodePool.translate_output_property" title="Permalink to this definition">¶</a></dt>
<dd><p>Provides subclasses of Resource an opportunity to translate names of output properties
into a format of their choosing before writing those properties to the resource object.</p>
<dl class="field-list simple">
<dt class="field-odd">Parameters</dt>
<dd class="field-odd"><p><strong>prop</strong> (<em>str</em>) – A property name.</p>
</dd>
<dt class="field-even">Returns</dt>
<dd class="field-even"><p>A potentially transformed property name.</p>
</dd>
<dt class="field-odd">Return type</dt>
<dd class="field-odd"><p>str</p>
</dd>
</dl>
</dd></dl>

<dl class="py method">
<dt id="pulumi_digitalocean.KubernetesNodePool.translate_input_property">
<code class="sig-name descname">translate_input_property</code><span class="sig-paren">(</span><em class="sig-param"><span class="n">prop</span></em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_digitalocean.KubernetesNodePool.translate_input_property" title="Permalink to this definition">¶</a></dt>
<dd><p>Provides subclasses of Resource an opportunity to translate names of input properties into
a format of their choosing before sending those properties to the Pulumi engine.</p>
<dl class="field-list simple">
<dt class="field-odd">Parameters</dt>
<dd class="field-odd"><p><strong>prop</strong> (<em>str</em>) – A property name.</p>
</dd>
<dt class="field-even">Returns</dt>
<dd class="field-even"><p>A potentially transformed property name.</p>
</dd>
<dt class="field-odd">Return type</dt>
<dd class="field-odd"><p>str</p>
</dd>
</dl>
</dd></dl>

</dd></dl>

<dl class="py class">
<dt id="pulumi_digitalocean.LoadBalancer">
<em class="property">class </em><code class="sig-prename descclassname">pulumi_digitalocean.</code><code class="sig-name descname">LoadBalancer</code><span class="sig-paren">(</span><em class="sig-param"><span class="n">resource_name</span></em>, <em class="sig-param"><span class="n">opts</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">algorithm</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">droplet_ids</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">droplet_tag</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">enable_backend_keepalive</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">enable_proxy_protocol</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">forwarding_rules</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">healthcheck</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">name</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">redirect_http_to_https</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">region</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">sticky_sessions</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">vpc_uuid</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">__props__</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">__name__</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">__opts__</span><span class="o">=</span><span class="default_value">None</span></em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_digitalocean.LoadBalancer" title="Permalink to this definition">¶</a></dt>
<dd><p>Provides a DigitalOcean Load Balancer resource. This can be used to create,
modify, and delete Load Balancers.</p>
<dl class="field-list simple">
<dt class="field-odd">Parameters</dt>
<dd class="field-odd"><ul class="simple">
<li><p><strong>resource_name</strong> (<em>str</em>) – The name of the resource.</p></li>
<li><p><strong>opts</strong> (<a class="reference internal" href="../pulumi/#pulumi.ResourceOptions" title="pulumi.ResourceOptions"><em>pulumi.ResourceOptions</em></a>) – Options for the resource.</p></li>
<li><p><strong>algorithm</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – The load balancing algorithm used to determine
which backend Droplet will be selected by a client. It must be either <code class="docutils literal notranslate"><span class="pre">round_robin</span></code>
or <code class="docutils literal notranslate"><span class="pre">least_connections</span></code>. The default value is <code class="docutils literal notranslate"><span class="pre">round_robin</span></code>.</p></li>
<li><p><strong>droplet_ids</strong> (<em>pulumi.Input</em><em>[</em><em>list</em><em>]</em>) – A list of the IDs of each droplet to be attached to the Load Balancer.</p></li>
<li><p><strong>droplet_tag</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – The name of a Droplet tag corresponding to Droplets to be assigned to the Load Balancer.</p></li>
<li><p><strong>enable_backend_keepalive</strong> (<em>pulumi.Input</em><em>[</em><em>bool</em><em>]</em>) – A boolean value indicating whether HTTP keepalive connections are maintained to target Droplets. Default value is <code class="docutils literal notranslate"><span class="pre">false</span></code>.</p></li>
<li><p><strong>enable_proxy_protocol</strong> (<em>pulumi.Input</em><em>[</em><em>bool</em><em>]</em>) – A boolean value indicating whether PROXY
Protocol should be used to pass information from connecting client requests to
the backend service. Default value is <code class="docutils literal notranslate"><span class="pre">false</span></code>.</p></li>
<li><p><strong>forwarding_rules</strong> (<em>pulumi.Input</em><em>[</em><em>list</em><em>]</em>) – A list of <code class="docutils literal notranslate"><span class="pre">forwarding_rule</span></code> to be assigned to the
Load Balancer. The <code class="docutils literal notranslate"><span class="pre">forwarding_rule</span></code> block is documented below.</p></li>
<li><p><strong>healthcheck</strong> (<em>pulumi.Input</em><em>[</em><em>dict</em><em>]</em>) – A <code class="docutils literal notranslate"><span class="pre">healthcheck</span></code> block to be assigned to the
Load Balancer. The <code class="docutils literal notranslate"><span class="pre">healthcheck</span></code> block is documented below. Only 1 healthcheck is allowed.</p></li>
<li><p><strong>name</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – The Load Balancer name</p></li>
<li><p><strong>redirect_http_to_https</strong> (<em>pulumi.Input</em><em>[</em><em>bool</em><em>]</em>) – A boolean value indicating whether
HTTP requests to the Load Balancer on port 80 will be redirected to HTTPS on port 443.
Default value is <code class="docutils literal notranslate"><span class="pre">false</span></code>.</p></li>
<li><p><strong>region</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – The region to start in</p></li>
<li><p><strong>sticky_sessions</strong> (<em>pulumi.Input</em><em>[</em><em>dict</em><em>]</em>) – A <code class="docutils literal notranslate"><span class="pre">sticky_sessions</span></code> block to be assigned to the
Load Balancer. The <code class="docutils literal notranslate"><span class="pre">sticky_sessions</span></code> block is documented below. Only 1 sticky_sessions block is allowed.</p></li>
<li><p><strong>vpc_uuid</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – The ID of the VPC where the load balancer will be located.</p></li>
</ul>
</dd>
</dl>
<p>The <strong>forwarding_rules</strong> object supports the following:</p>
<ul class="simple">
<li><p><code class="docutils literal notranslate"><span class="pre">certificate_id</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[str]</span></code>) - The ID of the TLS certificate to be used for SSL termination.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">entryPort</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[float]</span></code>) - An integer representing the port on which the Load Balancer instance will listen.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">entryProtocol</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[str]</span></code>) - The protocol used for traffic to the Load Balancer. The possible values are: <code class="docutils literal notranslate"><span class="pre">http</span></code>, <code class="docutils literal notranslate"><span class="pre">https</span></code>, <code class="docutils literal notranslate"><span class="pre">http2</span></code> or <code class="docutils literal notranslate"><span class="pre">tcp</span></code>.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">targetPort</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[float]</span></code>) - An integer representing the port on the backend Droplets to which the Load Balancer will send traffic.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">targetProtocol</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[str]</span></code>) - The protocol used for traffic from the Load Balancer to the backend Droplets. The possible values are: <code class="docutils literal notranslate"><span class="pre">http</span></code>, <code class="docutils literal notranslate"><span class="pre">https</span></code>, <code class="docutils literal notranslate"><span class="pre">http2</span></code> or <code class="docutils literal notranslate"><span class="pre">tcp</span></code>.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">tlsPassthrough</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[bool]</span></code>) - A boolean value indicating whether SSL encrypted traffic will be passed through to the backend Droplets. The default value is <code class="docutils literal notranslate"><span class="pre">false</span></code>.</p></li>
</ul>
<p>The <strong>healthcheck</strong> object supports the following:</p>
<ul class="simple">
<li><p><code class="docutils literal notranslate"><span class="pre">checkIntervalSeconds</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[float]</span></code>) - The number of seconds between between two consecutive health checks. If not specified, the default value is <code class="docutils literal notranslate"><span class="pre">10</span></code>.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">healthyThreshold</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[float]</span></code>) - The number of times a health check must pass for a backend Droplet to be marked “healthy” and be re-added to the pool. If not specified, the default value is <code class="docutils literal notranslate"><span class="pre">5</span></code>.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">path</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[str]</span></code>) - The path on the backend Droplets to which the Load Balancer instance will send a request.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">port</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[float]</span></code>) - An integer representing the port on the backend Droplets on which the health check will attempt a connection.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">protocol</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[str]</span></code>) - The protocol used for health checks sent to the backend Droplets. The possible values are <code class="docutils literal notranslate"><span class="pre">http</span></code> or <code class="docutils literal notranslate"><span class="pre">tcp</span></code>.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">responseTimeoutSeconds</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[float]</span></code>) - The number of seconds the Load Balancer instance will wait for a response until marking a health check as failed. If not specified, the default value is <code class="docutils literal notranslate"><span class="pre">5</span></code>.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">unhealthyThreshold</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[float]</span></code>) - The number of times a health check must fail for a backend Droplet to be marked “unhealthy” and be removed from the pool. If not specified, the default value is <code class="docutils literal notranslate"><span class="pre">3</span></code>.</p></li>
</ul>
<p>The <strong>sticky_sessions</strong> object supports the following:</p>
<ul class="simple">
<li><p><code class="docutils literal notranslate"><span class="pre">cookieName</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[str]</span></code>) - The name to be used for the cookie sent to the client. This attribute is required when using <code class="docutils literal notranslate"><span class="pre">cookies</span></code> for the sticky sessions type.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">cookieTtlSeconds</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[float]</span></code>) - The number of seconds until the cookie set by the Load Balancer expires. This attribute is required when using <code class="docutils literal notranslate"><span class="pre">cookies</span></code> for the sticky sessions type.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">type</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[str]</span></code>) - An attribute indicating how and if requests from a client will be persistently served by the same backend Droplet. The possible values are <code class="docutils literal notranslate"><span class="pre">cookies</span></code> or <code class="docutils literal notranslate"><span class="pre">none</span></code>. If not specified, the default value is <code class="docutils literal notranslate"><span class="pre">none</span></code>.</p></li>
</ul>
<dl class="py attribute">
<dt id="pulumi_digitalocean.LoadBalancer.algorithm">
<code class="sig-name descname">algorithm</code><em class="property">: pulumi.Output[str]</em><em class="property"> = None</em><a class="headerlink" href="#pulumi_digitalocean.LoadBalancer.algorithm" title="Permalink to this definition">¶</a></dt>
<dd><p>The load balancing algorithm used to determine
which backend Droplet will be selected by a client. It must be either <code class="docutils literal notranslate"><span class="pre">round_robin</span></code>
or <code class="docutils literal notranslate"><span class="pre">least_connections</span></code>. The default value is <code class="docutils literal notranslate"><span class="pre">round_robin</span></code>.</p>
</dd></dl>

<dl class="py attribute">
<dt id="pulumi_digitalocean.LoadBalancer.droplet_ids">
<code class="sig-name descname">droplet_ids</code><em class="property">: pulumi.Output[list]</em><em class="property"> = None</em><a class="headerlink" href="#pulumi_digitalocean.LoadBalancer.droplet_ids" title="Permalink to this definition">¶</a></dt>
<dd><p>A list of the IDs of each droplet to be attached to the Load Balancer.</p>
</dd></dl>

<dl class="py attribute">
<dt id="pulumi_digitalocean.LoadBalancer.droplet_tag">
<code class="sig-name descname">droplet_tag</code><em class="property">: pulumi.Output[str]</em><em class="property"> = None</em><a class="headerlink" href="#pulumi_digitalocean.LoadBalancer.droplet_tag" title="Permalink to this definition">¶</a></dt>
<dd><p>The name of a Droplet tag corresponding to Droplets to be assigned to the Load Balancer.</p>
</dd></dl>

<dl class="py attribute">
<dt id="pulumi_digitalocean.LoadBalancer.enable_backend_keepalive">
<code class="sig-name descname">enable_backend_keepalive</code><em class="property">: pulumi.Output[bool]</em><em class="property"> = None</em><a class="headerlink" href="#pulumi_digitalocean.LoadBalancer.enable_backend_keepalive" title="Permalink to this definition">¶</a></dt>
<dd><p>A boolean value indicating whether HTTP keepalive connections are maintained to target Droplets. Default value is <code class="docutils literal notranslate"><span class="pre">false</span></code>.</p>
</dd></dl>

<dl class="py attribute">
<dt id="pulumi_digitalocean.LoadBalancer.enable_proxy_protocol">
<code class="sig-name descname">enable_proxy_protocol</code><em class="property">: pulumi.Output[bool]</em><em class="property"> = None</em><a class="headerlink" href="#pulumi_digitalocean.LoadBalancer.enable_proxy_protocol" title="Permalink to this definition">¶</a></dt>
<dd><p>A boolean value indicating whether PROXY
Protocol should be used to pass information from connecting client requests to
the backend service. Default value is <code class="docutils literal notranslate"><span class="pre">false</span></code>.</p>
</dd></dl>

<dl class="py attribute">
<dt id="pulumi_digitalocean.LoadBalancer.forwarding_rules">
<code class="sig-name descname">forwarding_rules</code><em class="property">: pulumi.Output[list]</em><em class="property"> = None</em><a class="headerlink" href="#pulumi_digitalocean.LoadBalancer.forwarding_rules" title="Permalink to this definition">¶</a></dt>
<dd><p>A list of <code class="docutils literal notranslate"><span class="pre">forwarding_rule</span></code> to be assigned to the
Load Balancer. The <code class="docutils literal notranslate"><span class="pre">forwarding_rule</span></code> block is documented below.</p>
<ul class="simple">
<li><p><code class="docutils literal notranslate"><span class="pre">certificate_id</span></code> (<code class="docutils literal notranslate"><span class="pre">str</span></code>) - The ID of the TLS certificate to be used for SSL termination.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">entryPort</span></code> (<code class="docutils literal notranslate"><span class="pre">float</span></code>) - An integer representing the port on which the Load Balancer instance will listen.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">entryProtocol</span></code> (<code class="docutils literal notranslate"><span class="pre">str</span></code>) - The protocol used for traffic to the Load Balancer. The possible values are: <code class="docutils literal notranslate"><span class="pre">http</span></code>, <code class="docutils literal notranslate"><span class="pre">https</span></code>, <code class="docutils literal notranslate"><span class="pre">http2</span></code> or <code class="docutils literal notranslate"><span class="pre">tcp</span></code>.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">targetPort</span></code> (<code class="docutils literal notranslate"><span class="pre">float</span></code>) - An integer representing the port on the backend Droplets to which the Load Balancer will send traffic.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">targetProtocol</span></code> (<code class="docutils literal notranslate"><span class="pre">str</span></code>) - The protocol used for traffic from the Load Balancer to the backend Droplets. The possible values are: <code class="docutils literal notranslate"><span class="pre">http</span></code>, <code class="docutils literal notranslate"><span class="pre">https</span></code>, <code class="docutils literal notranslate"><span class="pre">http2</span></code> or <code class="docutils literal notranslate"><span class="pre">tcp</span></code>.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">tlsPassthrough</span></code> (<code class="docutils literal notranslate"><span class="pre">bool</span></code>) - A boolean value indicating whether SSL encrypted traffic will be passed through to the backend Droplets. The default value is <code class="docutils literal notranslate"><span class="pre">false</span></code>.</p></li>
</ul>
</dd></dl>

<dl class="py attribute">
<dt id="pulumi_digitalocean.LoadBalancer.healthcheck">
<code class="sig-name descname">healthcheck</code><em class="property">: pulumi.Output[dict]</em><em class="property"> = None</em><a class="headerlink" href="#pulumi_digitalocean.LoadBalancer.healthcheck" title="Permalink to this definition">¶</a></dt>
<dd><p>A <code class="docutils literal notranslate"><span class="pre">healthcheck</span></code> block to be assigned to the
Load Balancer. The <code class="docutils literal notranslate"><span class="pre">healthcheck</span></code> block is documented below. Only 1 healthcheck is allowed.</p>
<ul class="simple">
<li><p><code class="docutils literal notranslate"><span class="pre">checkIntervalSeconds</span></code> (<code class="docutils literal notranslate"><span class="pre">float</span></code>) - The number of seconds between between two consecutive health checks. If not specified, the default value is <code class="docutils literal notranslate"><span class="pre">10</span></code>.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">healthyThreshold</span></code> (<code class="docutils literal notranslate"><span class="pre">float</span></code>) - The number of times a health check must pass for a backend Droplet to be marked “healthy” and be re-added to the pool. If not specified, the default value is <code class="docutils literal notranslate"><span class="pre">5</span></code>.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">path</span></code> (<code class="docutils literal notranslate"><span class="pre">str</span></code>) - The path on the backend Droplets to which the Load Balancer instance will send a request.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">port</span></code> (<code class="docutils literal notranslate"><span class="pre">float</span></code>) - An integer representing the port on the backend Droplets on which the health check will attempt a connection.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">protocol</span></code> (<code class="docutils literal notranslate"><span class="pre">str</span></code>) - The protocol used for health checks sent to the backend Droplets. The possible values are <code class="docutils literal notranslate"><span class="pre">http</span></code> or <code class="docutils literal notranslate"><span class="pre">tcp</span></code>.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">responseTimeoutSeconds</span></code> (<code class="docutils literal notranslate"><span class="pre">float</span></code>) - The number of seconds the Load Balancer instance will wait for a response until marking a health check as failed. If not specified, the default value is <code class="docutils literal notranslate"><span class="pre">5</span></code>.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">unhealthyThreshold</span></code> (<code class="docutils literal notranslate"><span class="pre">float</span></code>) - The number of times a health check must fail for a backend Droplet to be marked “unhealthy” and be removed from the pool. If not specified, the default value is <code class="docutils literal notranslate"><span class="pre">3</span></code>.</p></li>
</ul>
</dd></dl>

<dl class="py attribute">
<dt id="pulumi_digitalocean.LoadBalancer.name">
<code class="sig-name descname">name</code><em class="property">: pulumi.Output[str]</em><em class="property"> = None</em><a class="headerlink" href="#pulumi_digitalocean.LoadBalancer.name" title="Permalink to this definition">¶</a></dt>
<dd><p>The Load Balancer name</p>
</dd></dl>

<dl class="py attribute">
<dt id="pulumi_digitalocean.LoadBalancer.redirect_http_to_https">
<code class="sig-name descname">redirect_http_to_https</code><em class="property">: pulumi.Output[bool]</em><em class="property"> = None</em><a class="headerlink" href="#pulumi_digitalocean.LoadBalancer.redirect_http_to_https" title="Permalink to this definition">¶</a></dt>
<dd><p>A boolean value indicating whether
HTTP requests to the Load Balancer on port 80 will be redirected to HTTPS on port 443.
Default value is <code class="docutils literal notranslate"><span class="pre">false</span></code>.</p>
</dd></dl>

<dl class="py attribute">
<dt id="pulumi_digitalocean.LoadBalancer.region">
<code class="sig-name descname">region</code><em class="property">: pulumi.Output[str]</em><em class="property"> = None</em><a class="headerlink" href="#pulumi_digitalocean.LoadBalancer.region" title="Permalink to this definition">¶</a></dt>
<dd><p>The region to start in</p>
</dd></dl>

<dl class="py attribute">
<dt id="pulumi_digitalocean.LoadBalancer.sticky_sessions">
<code class="sig-name descname">sticky_sessions</code><em class="property">: pulumi.Output[dict]</em><em class="property"> = None</em><a class="headerlink" href="#pulumi_digitalocean.LoadBalancer.sticky_sessions" title="Permalink to this definition">¶</a></dt>
<dd><p>A <code class="docutils literal notranslate"><span class="pre">sticky_sessions</span></code> block to be assigned to the
Load Balancer. The <code class="docutils literal notranslate"><span class="pre">sticky_sessions</span></code> block is documented below. Only 1 sticky_sessions block is allowed.</p>
<ul class="simple">
<li><p><code class="docutils literal notranslate"><span class="pre">cookieName</span></code> (<code class="docutils literal notranslate"><span class="pre">str</span></code>) - The name to be used for the cookie sent to the client. This attribute is required when using <code class="docutils literal notranslate"><span class="pre">cookies</span></code> for the sticky sessions type.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">cookieTtlSeconds</span></code> (<code class="docutils literal notranslate"><span class="pre">float</span></code>) - The number of seconds until the cookie set by the Load Balancer expires. This attribute is required when using <code class="docutils literal notranslate"><span class="pre">cookies</span></code> for the sticky sessions type.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">type</span></code> (<code class="docutils literal notranslate"><span class="pre">str</span></code>) - An attribute indicating how and if requests from a client will be persistently served by the same backend Droplet. The possible values are <code class="docutils literal notranslate"><span class="pre">cookies</span></code> or <code class="docutils literal notranslate"><span class="pre">none</span></code>. If not specified, the default value is <code class="docutils literal notranslate"><span class="pre">none</span></code>.</p></li>
</ul>
</dd></dl>

<dl class="py attribute">
<dt id="pulumi_digitalocean.LoadBalancer.urn">
<code class="sig-name descname">urn</code><em class="property">: pulumi.Output[str]</em><em class="property"> = None</em><a class="headerlink" href="#pulumi_digitalocean.LoadBalancer.urn" title="Permalink to this definition">¶</a></dt>
<dd><p>The uniform resource name for the Load Balancer</p>
</dd></dl>

<dl class="py attribute">
<dt id="pulumi_digitalocean.LoadBalancer.vpc_uuid">
<code class="sig-name descname">vpc_uuid</code><em class="property">: pulumi.Output[str]</em><em class="property"> = None</em><a class="headerlink" href="#pulumi_digitalocean.LoadBalancer.vpc_uuid" title="Permalink to this definition">¶</a></dt>
<dd><p>The ID of the VPC where the load balancer will be located.</p>
</dd></dl>

<dl class="py method">
<dt id="pulumi_digitalocean.LoadBalancer.get">
<em class="property">static </em><code class="sig-name descname">get</code><span class="sig-paren">(</span><em class="sig-param"><span class="n">resource_name</span></em>, <em class="sig-param"><span class="n">id</span></em>, <em class="sig-param"><span class="n">opts</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">algorithm</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">droplet_ids</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">droplet_tag</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">enable_backend_keepalive</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">enable_proxy_protocol</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">forwarding_rules</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">healthcheck</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">ip</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">name</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">redirect_http_to_https</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">region</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">status</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">sticky_sessions</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">urn</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">vpc_uuid</span><span class="o">=</span><span class="default_value">None</span></em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_digitalocean.LoadBalancer.get" title="Permalink to this definition">¶</a></dt>
<dd><p>Get an existing LoadBalancer resource’s state with the given name, id, and optional extra
properties used to qualify the lookup.</p>
<dl class="field-list simple">
<dt class="field-odd">Parameters</dt>
<dd class="field-odd"><ul class="simple">
<li><p><strong>resource_name</strong> (<em>str</em>) – The unique name of the resulting resource.</p></li>
<li><p><strong>id</strong> (<em>str</em>) – The unique provider ID of the resource to lookup.</p></li>
<li><p><strong>opts</strong> (<a class="reference internal" href="../pulumi/#pulumi.ResourceOptions" title="pulumi.ResourceOptions"><em>pulumi.ResourceOptions</em></a>) – Options for the resource.</p></li>
<li><p><strong>algorithm</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – The load balancing algorithm used to determine
which backend Droplet will be selected by a client. It must be either <code class="docutils literal notranslate"><span class="pre">round_robin</span></code>
or <code class="docutils literal notranslate"><span class="pre">least_connections</span></code>. The default value is <code class="docutils literal notranslate"><span class="pre">round_robin</span></code>.</p></li>
<li><p><strong>droplet_ids</strong> (<em>pulumi.Input</em><em>[</em><em>list</em><em>]</em>) – A list of the IDs of each droplet to be attached to the Load Balancer.</p></li>
<li><p><strong>droplet_tag</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – The name of a Droplet tag corresponding to Droplets to be assigned to the Load Balancer.</p></li>
<li><p><strong>enable_backend_keepalive</strong> (<em>pulumi.Input</em><em>[</em><em>bool</em><em>]</em>) – A boolean value indicating whether HTTP keepalive connections are maintained to target Droplets. Default value is <code class="docutils literal notranslate"><span class="pre">false</span></code>.</p></li>
<li><p><strong>enable_proxy_protocol</strong> (<em>pulumi.Input</em><em>[</em><em>bool</em><em>]</em>) – A boolean value indicating whether PROXY
Protocol should be used to pass information from connecting client requests to
the backend service. Default value is <code class="docutils literal notranslate"><span class="pre">false</span></code>.</p></li>
<li><p><strong>forwarding_rules</strong> (<em>pulumi.Input</em><em>[</em><em>list</em><em>]</em>) – A list of <code class="docutils literal notranslate"><span class="pre">forwarding_rule</span></code> to be assigned to the
Load Balancer. The <code class="docutils literal notranslate"><span class="pre">forwarding_rule</span></code> block is documented below.</p></li>
<li><p><strong>healthcheck</strong> (<em>pulumi.Input</em><em>[</em><em>dict</em><em>]</em>) – A <code class="docutils literal notranslate"><span class="pre">healthcheck</span></code> block to be assigned to the
Load Balancer. The <code class="docutils literal notranslate"><span class="pre">healthcheck</span></code> block is documented below. Only 1 healthcheck is allowed.</p></li>
<li><p><strong>name</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – The Load Balancer name</p></li>
<li><p><strong>redirect_http_to_https</strong> (<em>pulumi.Input</em><em>[</em><em>bool</em><em>]</em>) – A boolean value indicating whether
HTTP requests to the Load Balancer on port 80 will be redirected to HTTPS on port 443.
Default value is <code class="docutils literal notranslate"><span class="pre">false</span></code>.</p></li>
<li><p><strong>region</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – The region to start in</p></li>
<li><p><strong>sticky_sessions</strong> (<em>pulumi.Input</em><em>[</em><em>dict</em><em>]</em>) – A <code class="docutils literal notranslate"><span class="pre">sticky_sessions</span></code> block to be assigned to the
Load Balancer. The <code class="docutils literal notranslate"><span class="pre">sticky_sessions</span></code> block is documented below. Only 1 sticky_sessions block is allowed.</p></li>
<li><p><strong>urn</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – The uniform resource name for the Load Balancer</p></li>
<li><p><strong>vpc_uuid</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – The ID of the VPC where the load balancer will be located.</p></li>
</ul>
</dd>
</dl>
<p>The <strong>forwarding_rules</strong> object supports the following:</p>
<ul class="simple">
<li><p><code class="docutils literal notranslate"><span class="pre">certificate_id</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[str]</span></code>) - The ID of the TLS certificate to be used for SSL termination.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">entryPort</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[float]</span></code>) - An integer representing the port on which the Load Balancer instance will listen.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">entryProtocol</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[str]</span></code>) - The protocol used for traffic to the Load Balancer. The possible values are: <code class="docutils literal notranslate"><span class="pre">http</span></code>, <code class="docutils literal notranslate"><span class="pre">https</span></code>, <code class="docutils literal notranslate"><span class="pre">http2</span></code> or <code class="docutils literal notranslate"><span class="pre">tcp</span></code>.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">targetPort</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[float]</span></code>) - An integer representing the port on the backend Droplets to which the Load Balancer will send traffic.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">targetProtocol</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[str]</span></code>) - The protocol used for traffic from the Load Balancer to the backend Droplets. The possible values are: <code class="docutils literal notranslate"><span class="pre">http</span></code>, <code class="docutils literal notranslate"><span class="pre">https</span></code>, <code class="docutils literal notranslate"><span class="pre">http2</span></code> or <code class="docutils literal notranslate"><span class="pre">tcp</span></code>.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">tlsPassthrough</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[bool]</span></code>) - A boolean value indicating whether SSL encrypted traffic will be passed through to the backend Droplets. The default value is <code class="docutils literal notranslate"><span class="pre">false</span></code>.</p></li>
</ul>
<p>The <strong>healthcheck</strong> object supports the following:</p>
<ul class="simple">
<li><p><code class="docutils literal notranslate"><span class="pre">checkIntervalSeconds</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[float]</span></code>) - The number of seconds between between two consecutive health checks. If not specified, the default value is <code class="docutils literal notranslate"><span class="pre">10</span></code>.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">healthyThreshold</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[float]</span></code>) - The number of times a health check must pass for a backend Droplet to be marked “healthy” and be re-added to the pool. If not specified, the default value is <code class="docutils literal notranslate"><span class="pre">5</span></code>.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">path</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[str]</span></code>) - The path on the backend Droplets to which the Load Balancer instance will send a request.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">port</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[float]</span></code>) - An integer representing the port on the backend Droplets on which the health check will attempt a connection.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">protocol</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[str]</span></code>) - The protocol used for health checks sent to the backend Droplets. The possible values are <code class="docutils literal notranslate"><span class="pre">http</span></code> or <code class="docutils literal notranslate"><span class="pre">tcp</span></code>.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">responseTimeoutSeconds</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[float]</span></code>) - The number of seconds the Load Balancer instance will wait for a response until marking a health check as failed. If not specified, the default value is <code class="docutils literal notranslate"><span class="pre">5</span></code>.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">unhealthyThreshold</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[float]</span></code>) - The number of times a health check must fail for a backend Droplet to be marked “unhealthy” and be removed from the pool. If not specified, the default value is <code class="docutils literal notranslate"><span class="pre">3</span></code>.</p></li>
</ul>
<p>The <strong>sticky_sessions</strong> object supports the following:</p>
<ul class="simple">
<li><p><code class="docutils literal notranslate"><span class="pre">cookieName</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[str]</span></code>) - The name to be used for the cookie sent to the client. This attribute is required when using <code class="docutils literal notranslate"><span class="pre">cookies</span></code> for the sticky sessions type.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">cookieTtlSeconds</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[float]</span></code>) - The number of seconds until the cookie set by the Load Balancer expires. This attribute is required when using <code class="docutils literal notranslate"><span class="pre">cookies</span></code> for the sticky sessions type.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">type</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[str]</span></code>) - An attribute indicating how and if requests from a client will be persistently served by the same backend Droplet. The possible values are <code class="docutils literal notranslate"><span class="pre">cookies</span></code> or <code class="docutils literal notranslate"><span class="pre">none</span></code>. If not specified, the default value is <code class="docutils literal notranslate"><span class="pre">none</span></code>.</p></li>
</ul>
</dd></dl>

<dl class="py method">
<dt id="pulumi_digitalocean.LoadBalancer.translate_output_property">
<code class="sig-name descname">translate_output_property</code><span class="sig-paren">(</span><em class="sig-param"><span class="n">prop</span></em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_digitalocean.LoadBalancer.translate_output_property" title="Permalink to this definition">¶</a></dt>
<dd><p>Provides subclasses of Resource an opportunity to translate names of output properties
into a format of their choosing before writing those properties to the resource object.</p>
<dl class="field-list simple">
<dt class="field-odd">Parameters</dt>
<dd class="field-odd"><p><strong>prop</strong> (<em>str</em>) – A property name.</p>
</dd>
<dt class="field-even">Returns</dt>
<dd class="field-even"><p>A potentially transformed property name.</p>
</dd>
<dt class="field-odd">Return type</dt>
<dd class="field-odd"><p>str</p>
</dd>
</dl>
</dd></dl>

<dl class="py method">
<dt id="pulumi_digitalocean.LoadBalancer.translate_input_property">
<code class="sig-name descname">translate_input_property</code><span class="sig-paren">(</span><em class="sig-param"><span class="n">prop</span></em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_digitalocean.LoadBalancer.translate_input_property" title="Permalink to this definition">¶</a></dt>
<dd><p>Provides subclasses of Resource an opportunity to translate names of input properties into
a format of their choosing before sending those properties to the Pulumi engine.</p>
<dl class="field-list simple">
<dt class="field-odd">Parameters</dt>
<dd class="field-odd"><p><strong>prop</strong> (<em>str</em>) – A property name.</p>
</dd>
<dt class="field-even">Returns</dt>
<dd class="field-even"><p>A potentially transformed property name.</p>
</dd>
<dt class="field-odd">Return type</dt>
<dd class="field-odd"><p>str</p>
</dd>
</dl>
</dd></dl>

</dd></dl>

<dl class="py class">
<dt id="pulumi_digitalocean.Project">
<em class="property">class </em><code class="sig-prename descclassname">pulumi_digitalocean.</code><code class="sig-name descname">Project</code><span class="sig-paren">(</span><em class="sig-param"><span class="n">resource_name</span></em>, <em class="sig-param"><span class="n">opts</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">description</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">environment</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">name</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">purpose</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">resources</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">__props__</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">__name__</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">__opts__</span><span class="o">=</span><span class="default_value">None</span></em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_digitalocean.Project" title="Permalink to this definition">¶</a></dt>
<dd><p>Create a Project resource with the given unique name, props, and options.
:param str resource_name: The name of the resource.
:param pulumi.ResourceOptions opts: Options for the resource.
:param pulumi.Input[str] description: the description of the project
:param pulumi.Input[str] environment: the environment of the project’s resources. The possible values are: <code class="docutils literal notranslate"><span class="pre">Development</span></code>, <code class="docutils literal notranslate"><span class="pre">Staging</span></code>, <code class="docutils literal notranslate"><span class="pre">Production</span></code>)
:param pulumi.Input[str] name: The name of the Project
:param pulumi.Input[str] purpose: the purpose of the project, (Default: “Web Application”)
:param pulumi.Input[list] resources: a list of uniform resource names (URNs) for the resources associated with the project</p>
<dl class="py attribute">
<dt id="pulumi_digitalocean.Project.created_at">
<code class="sig-name descname">created_at</code><em class="property">: pulumi.Output[str]</em><em class="property"> = None</em><a class="headerlink" href="#pulumi_digitalocean.Project.created_at" title="Permalink to this definition">¶</a></dt>
<dd><p>the date and time when the project was created, (ISO8601)</p>
</dd></dl>

<dl class="py attribute">
<dt id="pulumi_digitalocean.Project.description">
<code class="sig-name descname">description</code><em class="property">: pulumi.Output[str]</em><em class="property"> = None</em><a class="headerlink" href="#pulumi_digitalocean.Project.description" title="Permalink to this definition">¶</a></dt>
<dd><p>the description of the project</p>
</dd></dl>

<dl class="py attribute">
<dt id="pulumi_digitalocean.Project.environment">
<code class="sig-name descname">environment</code><em class="property">: pulumi.Output[str]</em><em class="property"> = None</em><a class="headerlink" href="#pulumi_digitalocean.Project.environment" title="Permalink to this definition">¶</a></dt>
<dd><p>the environment of the project’s resources. The possible values are: <code class="docutils literal notranslate"><span class="pre">Development</span></code>, <code class="docutils literal notranslate"><span class="pre">Staging</span></code>, <code class="docutils literal notranslate"><span class="pre">Production</span></code>)</p>
</dd></dl>

<dl class="py attribute">
<dt id="pulumi_digitalocean.Project.name">
<code class="sig-name descname">name</code><em class="property">: pulumi.Output[str]</em><em class="property"> = None</em><a class="headerlink" href="#pulumi_digitalocean.Project.name" title="Permalink to this definition">¶</a></dt>
<dd><p>The name of the Project</p>
</dd></dl>

<dl class="py attribute">
<dt id="pulumi_digitalocean.Project.owner_id">
<code class="sig-name descname">owner_id</code><em class="property">: pulumi.Output[float]</em><em class="property"> = None</em><a class="headerlink" href="#pulumi_digitalocean.Project.owner_id" title="Permalink to this definition">¶</a></dt>
<dd><p>the id of the project owner.</p>
</dd></dl>

<dl class="py attribute">
<dt id="pulumi_digitalocean.Project.owner_uuid">
<code class="sig-name descname">owner_uuid</code><em class="property">: pulumi.Output[str]</em><em class="property"> = None</em><a class="headerlink" href="#pulumi_digitalocean.Project.owner_uuid" title="Permalink to this definition">¶</a></dt>
<dd><p>the unique universal identifier of the project owner.</p>
</dd></dl>

<dl class="py attribute">
<dt id="pulumi_digitalocean.Project.purpose">
<code class="sig-name descname">purpose</code><em class="property">: pulumi.Output[str]</em><em class="property"> = None</em><a class="headerlink" href="#pulumi_digitalocean.Project.purpose" title="Permalink to this definition">¶</a></dt>
<dd><p>the purpose of the project, (Default: “Web Application”)</p>
</dd></dl>

<dl class="py attribute">
<dt id="pulumi_digitalocean.Project.resources">
<code class="sig-name descname">resources</code><em class="property">: pulumi.Output[list]</em><em class="property"> = None</em><a class="headerlink" href="#pulumi_digitalocean.Project.resources" title="Permalink to this definition">¶</a></dt>
<dd><p>a list of uniform resource names (URNs) for the resources associated with the project</p>
</dd></dl>

<dl class="py attribute">
<dt id="pulumi_digitalocean.Project.updated_at">
<code class="sig-name descname">updated_at</code><em class="property">: pulumi.Output[str]</em><em class="property"> = None</em><a class="headerlink" href="#pulumi_digitalocean.Project.updated_at" title="Permalink to this definition">¶</a></dt>
<dd><p>the date and time when the project was last updated, (ISO8601)</p>
</dd></dl>

<dl class="py method">
<dt id="pulumi_digitalocean.Project.get">
<em class="property">static </em><code class="sig-name descname">get</code><span class="sig-paren">(</span><em class="sig-param"><span class="n">resource_name</span></em>, <em class="sig-param"><span class="n">id</span></em>, <em class="sig-param"><span class="n">opts</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">created_at</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">description</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">environment</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">is_default</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">name</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">owner_id</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">owner_uuid</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">purpose</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">resources</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">updated_at</span><span class="o">=</span><span class="default_value">None</span></em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_digitalocean.Project.get" title="Permalink to this definition">¶</a></dt>
<dd><p>Get an existing Project resource’s state with the given name, id, and optional extra
properties used to qualify the lookup.</p>
<dl class="field-list simple">
<dt class="field-odd">Parameters</dt>
<dd class="field-odd"><ul class="simple">
<li><p><strong>resource_name</strong> (<em>str</em>) – The unique name of the resulting resource.</p></li>
<li><p><strong>id</strong> (<em>str</em>) – The unique provider ID of the resource to lookup.</p></li>
<li><p><strong>opts</strong> (<a class="reference internal" href="../pulumi/#pulumi.ResourceOptions" title="pulumi.ResourceOptions"><em>pulumi.ResourceOptions</em></a>) – Options for the resource.</p></li>
<li><p><strong>created_at</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – the date and time when the project was created, (ISO8601)</p></li>
<li><p><strong>description</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – the description of the project</p></li>
<li><p><strong>environment</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – the environment of the project’s resources. The possible values are: <code class="docutils literal notranslate"><span class="pre">Development</span></code>, <code class="docutils literal notranslate"><span class="pre">Staging</span></code>, <code class="docutils literal notranslate"><span class="pre">Production</span></code>)</p></li>
<li><p><strong>name</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – The name of the Project</p></li>
<li><p><strong>owner_id</strong> (<em>pulumi.Input</em><em>[</em><em>float</em><em>]</em>) – the id of the project owner.</p></li>
<li><p><strong>owner_uuid</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – the unique universal identifier of the project owner.</p></li>
<li><p><strong>purpose</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – the purpose of the project, (Default: “Web Application”)</p></li>
<li><p><strong>resources</strong> (<em>pulumi.Input</em><em>[</em><em>list</em><em>]</em>) – a list of uniform resource names (URNs) for the resources associated with the project</p></li>
<li><p><strong>updated_at</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – the date and time when the project was last updated, (ISO8601)</p></li>
</ul>
</dd>
</dl>
</dd></dl>

<dl class="py method">
<dt id="pulumi_digitalocean.Project.translate_output_property">
<code class="sig-name descname">translate_output_property</code><span class="sig-paren">(</span><em class="sig-param"><span class="n">prop</span></em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_digitalocean.Project.translate_output_property" title="Permalink to this definition">¶</a></dt>
<dd><p>Provides subclasses of Resource an opportunity to translate names of output properties
into a format of their choosing before writing those properties to the resource object.</p>
<dl class="field-list simple">
<dt class="field-odd">Parameters</dt>
<dd class="field-odd"><p><strong>prop</strong> (<em>str</em>) – A property name.</p>
</dd>
<dt class="field-even">Returns</dt>
<dd class="field-even"><p>A potentially transformed property name.</p>
</dd>
<dt class="field-odd">Return type</dt>
<dd class="field-odd"><p>str</p>
</dd>
</dl>
</dd></dl>

<dl class="py method">
<dt id="pulumi_digitalocean.Project.translate_input_property">
<code class="sig-name descname">translate_input_property</code><span class="sig-paren">(</span><em class="sig-param"><span class="n">prop</span></em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_digitalocean.Project.translate_input_property" title="Permalink to this definition">¶</a></dt>
<dd><p>Provides subclasses of Resource an opportunity to translate names of input properties into
a format of their choosing before sending those properties to the Pulumi engine.</p>
<dl class="field-list simple">
<dt class="field-odd">Parameters</dt>
<dd class="field-odd"><p><strong>prop</strong> (<em>str</em>) – A property name.</p>
</dd>
<dt class="field-even">Returns</dt>
<dd class="field-even"><p>A potentially transformed property name.</p>
</dd>
<dt class="field-odd">Return type</dt>
<dd class="field-odd"><p>str</p>
</dd>
</dl>
</dd></dl>

</dd></dl>

<dl class="py class">
<dt id="pulumi_digitalocean.Provider">
<em class="property">class </em><code class="sig-prename descclassname">pulumi_digitalocean.</code><code class="sig-name descname">Provider</code><span class="sig-paren">(</span><em class="sig-param"><span class="n">resource_name</span></em>, <em class="sig-param"><span class="n">opts</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">api_endpoint</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">spaces_access_id</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">spaces_endpoint</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">spaces_secret_key</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">token</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">__props__</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">__name__</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">__opts__</span><span class="o">=</span><span class="default_value">None</span></em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_digitalocean.Provider" title="Permalink to this definition">¶</a></dt>
<dd><p>The provider type for the digitalocean package. By default, resources use package-wide configuration
settings, however an explicit <code class="docutils literal notranslate"><span class="pre">Provider</span></code> instance may be created and passed during resource
construction to achieve fine-grained programmatic control over provider settings. See the
<a class="reference external" href="https://www.pulumi.com/docs/reference/programming-model/#providers">documentation</a> for more information.</p>
<dl class="field-list simple">
<dt class="field-odd">Parameters</dt>
<dd class="field-odd"><ul class="simple">
<li><p><strong>resource_name</strong> (<em>str</em>) – The name of the resource.</p></li>
<li><p><strong>opts</strong> (<a class="reference internal" href="../pulumi/#pulumi.ResourceOptions" title="pulumi.ResourceOptions"><em>pulumi.ResourceOptions</em></a>) – Options for the resource.</p></li>
<li><p><strong>api_endpoint</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – The URL to use for the DigitalOcean API.</p></li>
<li><p><strong>spaces_access_id</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – The access key ID for Spaces API operations.</p></li>
<li><p><strong>spaces_endpoint</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – The URL to use for the DigitalOcean Spaces API.</p></li>
<li><p><strong>spaces_secret_key</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – The secret access key for Spaces API operations.</p></li>
<li><p><strong>token</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – The token key for API operations.</p></li>
</ul>
</dd>
</dl>
<dl class="py method">
<dt id="pulumi_digitalocean.Provider.translate_output_property">
<code class="sig-name descname">translate_output_property</code><span class="sig-paren">(</span><em class="sig-param"><span class="n">prop</span></em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_digitalocean.Provider.translate_output_property" title="Permalink to this definition">¶</a></dt>
<dd><p>Provides subclasses of Resource an opportunity to translate names of output properties
into a format of their choosing before writing those properties to the resource object.</p>
<dl class="field-list simple">
<dt class="field-odd">Parameters</dt>
<dd class="field-odd"><p><strong>prop</strong> (<em>str</em>) – A property name.</p>
</dd>
<dt class="field-even">Returns</dt>
<dd class="field-even"><p>A potentially transformed property name.</p>
</dd>
<dt class="field-odd">Return type</dt>
<dd class="field-odd"><p>str</p>
</dd>
</dl>
</dd></dl>

<dl class="py method">
<dt id="pulumi_digitalocean.Provider.translate_input_property">
<code class="sig-name descname">translate_input_property</code><span class="sig-paren">(</span><em class="sig-param"><span class="n">prop</span></em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_digitalocean.Provider.translate_input_property" title="Permalink to this definition">¶</a></dt>
<dd><p>Provides subclasses of Resource an opportunity to translate names of input properties into
a format of their choosing before sending those properties to the Pulumi engine.</p>
<dl class="field-list simple">
<dt class="field-odd">Parameters</dt>
<dd class="field-odd"><p><strong>prop</strong> (<em>str</em>) – A property name.</p>
</dd>
<dt class="field-even">Returns</dt>
<dd class="field-even"><p>A potentially transformed property name.</p>
</dd>
<dt class="field-odd">Return type</dt>
<dd class="field-odd"><p>str</p>
</dd>
</dl>
</dd></dl>

</dd></dl>

<dl class="py class">
<dt id="pulumi_digitalocean.SpacesBucket">
<em class="property">class </em><code class="sig-prename descclassname">pulumi_digitalocean.</code><code class="sig-name descname">SpacesBucket</code><span class="sig-paren">(</span><em class="sig-param"><span class="n">resource_name</span></em>, <em class="sig-param"><span class="n">opts</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">acl</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">cors_rules</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">force_destroy</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">lifecycle_rules</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">name</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">region</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">versioning</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">__props__</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">__name__</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">__opts__</span><span class="o">=</span><span class="default_value">None</span></em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_digitalocean.SpacesBucket" title="Permalink to this definition">¶</a></dt>
<dd><p>Provides a bucket resource for Spaces, DigitalOcean’s object storage product.</p>
<p>The <a class="reference external" href="https://developers.digitalocean.com/documentation/spaces/">Spaces API</a> was
designed to be interoperable with Amazon’s AWS S3 API. This allows users to
interact with the service while using the tools they already know. Spaces
mirrors S3’s authentication framework and requests to Spaces require a key pair
similar to Amazon’s Access ID and Secret Key.</p>
<p>The authentication requirement can be met by either setting the
<code class="docutils literal notranslate"><span class="pre">SPACES_ACCESS_KEY_ID</span></code> and <code class="docutils literal notranslate"><span class="pre">SPACES_SECRET_ACCESS_KEY</span></code> environment variables or
the provider’s <code class="docutils literal notranslate"><span class="pre">spaces_access_id</span></code> and <code class="docutils literal notranslate"><span class="pre">spaces_secret_key</span></code> arguments to the
access ID and secret you generate via the DigitalOcean control panel. For
example:</p>
<div class="highlight-python notranslate"><div class="highlight"><pre><span></span><span class="kn">import</span> <span class="nn">pulumi</span>
<span class="kn">import</span> <span class="nn">pulumi_digitalocean</span> <span class="k">as</span> <span class="nn">digitalocean</span>

<span class="n">static_assets</span> <span class="o">=</span> <span class="n">digitalocean</span><span class="o">.</span><span class="n">SpacesBucket</span><span class="p">(</span><span class="s2">&quot;static-assets&quot;</span><span class="p">)</span>
</pre></div>
</div>
<p>For more information, See <a class="reference external" href="https://www.digitalocean.com/community/tutorials/an-introduction-to-digitalocean-spaces">An Introduction to DigitalOcean Spaces</a></p>
<div class="highlight-python notranslate"><div class="highlight"><pre><span></span><span class="kn">import</span> <span class="nn">pulumi</span>
<span class="kn">import</span> <span class="nn">pulumi_digitalocean</span> <span class="k">as</span> <span class="nn">digitalocean</span>

<span class="n">foobar</span> <span class="o">=</span> <span class="n">digitalocean</span><span class="o">.</span><span class="n">SpacesBucket</span><span class="p">(</span><span class="s2">&quot;foobar&quot;</span><span class="p">,</span> <span class="n">region</span><span class="o">=</span><span class="s2">&quot;nyc3&quot;</span><span class="p">)</span>
</pre></div>
</div>
<div class="highlight-python notranslate"><div class="highlight"><pre><span></span><span class="kn">import</span> <span class="nn">pulumi</span>
<span class="kn">import</span> <span class="nn">pulumi_digitalocean</span> <span class="k">as</span> <span class="nn">digitalocean</span>

<span class="n">foobar</span> <span class="o">=</span> <span class="n">digitalocean</span><span class="o">.</span><span class="n">SpacesBucket</span><span class="p">(</span><span class="s2">&quot;foobar&quot;</span><span class="p">,</span>
    <span class="n">cors_rules</span><span class="o">=</span><span class="p">[</span>
        <span class="p">{</span>
            <span class="s2">&quot;allowedHeaders&quot;</span><span class="p">:</span> <span class="p">[</span><span class="s2">&quot;*&quot;</span><span class="p">],</span>
            <span class="s2">&quot;allowedMethods&quot;</span><span class="p">:</span> <span class="p">[</span><span class="s2">&quot;GET&quot;</span><span class="p">],</span>
            <span class="s2">&quot;allowedOrigins&quot;</span><span class="p">:</span> <span class="p">[</span><span class="s2">&quot;*&quot;</span><span class="p">],</span>
            <span class="s2">&quot;maxAgeSeconds&quot;</span><span class="p">:</span> <span class="mi">3000</span><span class="p">,</span>
        <span class="p">},</span>
        <span class="p">{</span>
            <span class="s2">&quot;allowedHeaders&quot;</span><span class="p">:</span> <span class="p">[</span><span class="s2">&quot;*&quot;</span><span class="p">],</span>
            <span class="s2">&quot;allowedMethods&quot;</span><span class="p">:</span> <span class="p">[</span>
                <span class="s2">&quot;PUT&quot;</span><span class="p">,</span>
                <span class="s2">&quot;POST&quot;</span><span class="p">,</span>
                <span class="s2">&quot;DELETE&quot;</span><span class="p">,</span>
            <span class="p">],</span>
            <span class="s2">&quot;allowedOrigins&quot;</span><span class="p">:</span> <span class="p">[</span><span class="s2">&quot;https://www.example.com&quot;</span><span class="p">],</span>
            <span class="s2">&quot;maxAgeSeconds&quot;</span><span class="p">:</span> <span class="mi">3000</span><span class="p">,</span>
        <span class="p">},</span>
    <span class="p">],</span>
    <span class="n">region</span><span class="o">=</span><span class="s2">&quot;nyc3&quot;</span><span class="p">)</span>
</pre></div>
</div>
<dl class="field-list simple">
<dt class="field-odd">Parameters</dt>
<dd class="field-odd"><ul class="simple">
<li><p><strong>resource_name</strong> (<em>str</em>) – The name of the resource.</p></li>
<li><p><strong>opts</strong> (<a class="reference internal" href="../pulumi/#pulumi.ResourceOptions" title="pulumi.ResourceOptions"><em>pulumi.ResourceOptions</em></a>) – Options for the resource.</p></li>
<li><p><strong>acl</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – Canned ACL applied on bucket creation (<code class="docutils literal notranslate"><span class="pre">private</span></code> or <code class="docutils literal notranslate"><span class="pre">public-read</span></code>)</p></li>
<li><p><strong>cors_rules</strong> (<em>pulumi.Input</em><em>[</em><em>list</em><em>]</em>) – A rule of Cross-Origin Resource Sharing (documented below).</p></li>
<li><p><strong>force_destroy</strong> (<em>pulumi.Input</em><em>[</em><em>bool</em><em>]</em>) – Unless <code class="docutils literal notranslate"><span class="pre">true</span></code>, the bucket will only be destroyed if empty (Defaults to <code class="docutils literal notranslate"><span class="pre">false</span></code>)</p></li>
<li><p><strong>lifecycle_rules</strong> (<em>pulumi.Input</em><em>[</em><em>list</em><em>]</em>) – A configuration of object lifecycle management (documented below).</p></li>
<li><p><strong>name</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – The name of the bucket</p></li>
<li><p><strong>region</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – The region where the bucket resides (Defaults to <code class="docutils literal notranslate"><span class="pre">nyc3</span></code>)</p></li>
<li><p><strong>versioning</strong> (<em>pulumi.Input</em><em>[</em><em>dict</em><em>]</em>) – A state of versioning (documented below)</p></li>
</ul>
</dd>
</dl>
<p>The <strong>cors_rules</strong> object supports the following:</p>
<ul class="simple">
<li><p><code class="docutils literal notranslate"><span class="pre">allowedHeaders</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[list]</span></code>) - A list of headers that will be included in the CORS preflight request’s <code class="docutils literal notranslate"><span class="pre">Access-Control-Request-Headers</span></code>. A header may contain one wildcard (e.g. <code class="docutils literal notranslate"><span class="pre">x-amz-*</span></code>).</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">allowedMethods</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[list]</span></code>) - A list of HTTP methods (e.g. <code class="docutils literal notranslate"><span class="pre">GET</span></code>) which are allowed from the specified origin.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">allowedOrigins</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[list]</span></code>) - A list of hosts from which requests using the specified methods are allowed. A host may contain one wildcard (e.g. <a class="reference external" href="http://">http://</a><a href="#id13"><span class="problematic" id="id14">*</span></a>.example.com).</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">maxAgeSeconds</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[float]</span></code>) - The time in seconds that browser can cache the response for a preflight request.</p></li>
</ul>
<p>The <strong>lifecycle_rules</strong> object supports the following:</p>
<ul class="simple">
<li><p><code class="docutils literal notranslate"><span class="pre">abortIncompleteMultipartUploadDays</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[float]</span></code>) - Specifies the number of days after initiating a multipart
upload when the multipart upload must be completed or else Spaces will abort the upload.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">enabled</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[bool]</span></code>) - Specifies lifecycle rule status.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">expiration</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[dict]</span></code>) - Specifies a time period after which applicable objects expire (documented below).</p>
<ul>
<li><p><code class="docutils literal notranslate"><span class="pre">date</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[str]</span></code>) - Specifies the date/time after which you want applicable objects to expire. The argument uses
RFC3339 format, e.g. “2020-03-22T15:03:55Z” or parts thereof e.g. “2019-02-28”.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">days</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[float]</span></code>) - Specifies the number of days after object creation when the applicable objects will expire.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">expiredObjectDeleteMarker</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[bool]</span></code>) - On a versioned bucket (versioning-enabled or versioning-suspended
bucket), setting this to true directs Spaces to delete expired object delete markers.</p></li>
</ul>
</li>
<li><p><code class="docutils literal notranslate"><span class="pre">id</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[str]</span></code>) - Unique identifier for the rule.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">noncurrentVersionExpiration</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[dict]</span></code>) - Specifies when non-current object versions expire (documented below).</p>
<ul>
<li><p><code class="docutils literal notranslate"><span class="pre">days</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[float]</span></code>) - Specifies the number of days after which an object’s non-current versions expire.</p></li>
</ul>
</li>
<li><p><code class="docutils literal notranslate"><span class="pre">prefix</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[str]</span></code>) - Object key prefix identifying one or more objects to which the rule applies.</p></li>
</ul>
<p>The <strong>versioning</strong> object supports the following:</p>
<ul class="simple">
<li><p><code class="docutils literal notranslate"><span class="pre">enabled</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[bool]</span></code>) - Enable versioning. Once you version-enable a bucket, it can never return to an unversioned
state. You can, however, suspend versioning on that bucket.</p></li>
</ul>
<dl class="py attribute">
<dt id="pulumi_digitalocean.SpacesBucket.acl">
<code class="sig-name descname">acl</code><em class="property">: pulumi.Output[str]</em><em class="property"> = None</em><a class="headerlink" href="#pulumi_digitalocean.SpacesBucket.acl" title="Permalink to this definition">¶</a></dt>
<dd><p>Canned ACL applied on bucket creation (<code class="docutils literal notranslate"><span class="pre">private</span></code> or <code class="docutils literal notranslate"><span class="pre">public-read</span></code>)</p>
</dd></dl>

<dl class="py attribute">
<dt id="pulumi_digitalocean.SpacesBucket.bucket_domain_name">
<code class="sig-name descname">bucket_domain_name</code><em class="property">: pulumi.Output[str]</em><em class="property"> = None</em><a class="headerlink" href="#pulumi_digitalocean.SpacesBucket.bucket_domain_name" title="Permalink to this definition">¶</a></dt>
<dd><p>The FQDN of the bucket (e.g. bucket-name.nyc3.digitaloceanspaces.com)</p>
</dd></dl>

<dl class="py attribute">
<dt id="pulumi_digitalocean.SpacesBucket.cors_rules">
<code class="sig-name descname">cors_rules</code><em class="property">: pulumi.Output[list]</em><em class="property"> = None</em><a class="headerlink" href="#pulumi_digitalocean.SpacesBucket.cors_rules" title="Permalink to this definition">¶</a></dt>
<dd><p>A rule of Cross-Origin Resource Sharing (documented below).</p>
<ul class="simple">
<li><p><code class="docutils literal notranslate"><span class="pre">allowedHeaders</span></code> (<code class="docutils literal notranslate"><span class="pre">list</span></code>) - A list of headers that will be included in the CORS preflight request’s <code class="docutils literal notranslate"><span class="pre">Access-Control-Request-Headers</span></code>. A header may contain one wildcard (e.g. <code class="docutils literal notranslate"><span class="pre">x-amz-*</span></code>).</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">allowedMethods</span></code> (<code class="docutils literal notranslate"><span class="pre">list</span></code>) - A list of HTTP methods (e.g. <code class="docutils literal notranslate"><span class="pre">GET</span></code>) which are allowed from the specified origin.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">allowedOrigins</span></code> (<code class="docutils literal notranslate"><span class="pre">list</span></code>) - A list of hosts from which requests using the specified methods are allowed. A host may contain one wildcard (e.g. <a class="reference external" href="http://">http://</a><a href="#id15"><span class="problematic" id="id16">*</span></a>.example.com).</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">maxAgeSeconds</span></code> (<code class="docutils literal notranslate"><span class="pre">float</span></code>) - The time in seconds that browser can cache the response for a preflight request.</p></li>
</ul>
</dd></dl>

<dl class="py attribute">
<dt id="pulumi_digitalocean.SpacesBucket.force_destroy">
<code class="sig-name descname">force_destroy</code><em class="property">: pulumi.Output[bool]</em><em class="property"> = None</em><a class="headerlink" href="#pulumi_digitalocean.SpacesBucket.force_destroy" title="Permalink to this definition">¶</a></dt>
<dd><p>Unless <code class="docutils literal notranslate"><span class="pre">true</span></code>, the bucket will only be destroyed if empty (Defaults to <code class="docutils literal notranslate"><span class="pre">false</span></code>)</p>
</dd></dl>

<dl class="py attribute">
<dt id="pulumi_digitalocean.SpacesBucket.lifecycle_rules">
<code class="sig-name descname">lifecycle_rules</code><em class="property">: pulumi.Output[list]</em><em class="property"> = None</em><a class="headerlink" href="#pulumi_digitalocean.SpacesBucket.lifecycle_rules" title="Permalink to this definition">¶</a></dt>
<dd><p>A configuration of object lifecycle management (documented below).</p>
<ul class="simple">
<li><p><code class="docutils literal notranslate"><span class="pre">abortIncompleteMultipartUploadDays</span></code> (<code class="docutils literal notranslate"><span class="pre">float</span></code>) - Specifies the number of days after initiating a multipart
upload when the multipart upload must be completed or else Spaces will abort the upload.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">enabled</span></code> (<code class="docutils literal notranslate"><span class="pre">bool</span></code>) - Specifies lifecycle rule status.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">expiration</span></code> (<code class="docutils literal notranslate"><span class="pre">dict</span></code>) - Specifies a time period after which applicable objects expire (documented below).</p>
<ul>
<li><p><code class="docutils literal notranslate"><span class="pre">date</span></code> (<code class="docutils literal notranslate"><span class="pre">str</span></code>) - Specifies the date/time after which you want applicable objects to expire. The argument uses
RFC3339 format, e.g. “2020-03-22T15:03:55Z” or parts thereof e.g. “2019-02-28”.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">days</span></code> (<code class="docutils literal notranslate"><span class="pre">float</span></code>) - Specifies the number of days after object creation when the applicable objects will expire.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">expiredObjectDeleteMarker</span></code> (<code class="docutils literal notranslate"><span class="pre">bool</span></code>) - On a versioned bucket (versioning-enabled or versioning-suspended
bucket), setting this to true directs Spaces to delete expired object delete markers.</p></li>
</ul>
</li>
<li><p><code class="docutils literal notranslate"><span class="pre">id</span></code> (<code class="docutils literal notranslate"><span class="pre">str</span></code>) - Unique identifier for the rule.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">noncurrentVersionExpiration</span></code> (<code class="docutils literal notranslate"><span class="pre">dict</span></code>) - Specifies when non-current object versions expire (documented below).</p>
<ul>
<li><p><code class="docutils literal notranslate"><span class="pre">days</span></code> (<code class="docutils literal notranslate"><span class="pre">float</span></code>) - Specifies the number of days after which an object’s non-current versions expire.</p></li>
</ul>
</li>
<li><p><code class="docutils literal notranslate"><span class="pre">prefix</span></code> (<code class="docutils literal notranslate"><span class="pre">str</span></code>) - Object key prefix identifying one or more objects to which the rule applies.</p></li>
</ul>
</dd></dl>

<dl class="py attribute">
<dt id="pulumi_digitalocean.SpacesBucket.name">
<code class="sig-name descname">name</code><em class="property">: pulumi.Output[str]</em><em class="property"> = None</em><a class="headerlink" href="#pulumi_digitalocean.SpacesBucket.name" title="Permalink to this definition">¶</a></dt>
<dd><p>The name of the bucket</p>
</dd></dl>

<dl class="py attribute">
<dt id="pulumi_digitalocean.SpacesBucket.region">
<code class="sig-name descname">region</code><em class="property">: pulumi.Output[str]</em><em class="property"> = None</em><a class="headerlink" href="#pulumi_digitalocean.SpacesBucket.region" title="Permalink to this definition">¶</a></dt>
<dd><p>The region where the bucket resides (Defaults to <code class="docutils literal notranslate"><span class="pre">nyc3</span></code>)</p>
</dd></dl>

<dl class="py attribute">
<dt id="pulumi_digitalocean.SpacesBucket.urn">
<code class="sig-name descname">urn</code><em class="property">: pulumi.Output[str]</em><em class="property"> = None</em><a class="headerlink" href="#pulumi_digitalocean.SpacesBucket.urn" title="Permalink to this definition">¶</a></dt>
<dd><p>The uniform resource name for the bucket</p>
</dd></dl>

<dl class="py attribute">
<dt id="pulumi_digitalocean.SpacesBucket.versioning">
<code class="sig-name descname">versioning</code><em class="property">: pulumi.Output[dict]</em><em class="property"> = None</em><a class="headerlink" href="#pulumi_digitalocean.SpacesBucket.versioning" title="Permalink to this definition">¶</a></dt>
<dd><p>A state of versioning (documented below)</p>
<ul class="simple">
<li><p><code class="docutils literal notranslate"><span class="pre">enabled</span></code> (<code class="docutils literal notranslate"><span class="pre">bool</span></code>) - Enable versioning. Once you version-enable a bucket, it can never return to an unversioned
state. You can, however, suspend versioning on that bucket.</p></li>
</ul>
</dd></dl>

<dl class="py method">
<dt id="pulumi_digitalocean.SpacesBucket.get">
<em class="property">static </em><code class="sig-name descname">get</code><span class="sig-paren">(</span><em class="sig-param"><span class="n">resource_name</span></em>, <em class="sig-param"><span class="n">id</span></em>, <em class="sig-param"><span class="n">opts</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">acl</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">bucket_domain_name</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">cors_rules</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">force_destroy</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">lifecycle_rules</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">name</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">region</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">urn</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">versioning</span><span class="o">=</span><span class="default_value">None</span></em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_digitalocean.SpacesBucket.get" title="Permalink to this definition">¶</a></dt>
<dd><p>Get an existing SpacesBucket resource’s state with the given name, id, and optional extra
properties used to qualify the lookup.</p>
<dl class="field-list simple">
<dt class="field-odd">Parameters</dt>
<dd class="field-odd"><ul class="simple">
<li><p><strong>resource_name</strong> (<em>str</em>) – The unique name of the resulting resource.</p></li>
<li><p><strong>id</strong> (<em>str</em>) – The unique provider ID of the resource to lookup.</p></li>
<li><p><strong>opts</strong> (<a class="reference internal" href="../pulumi/#pulumi.ResourceOptions" title="pulumi.ResourceOptions"><em>pulumi.ResourceOptions</em></a>) – Options for the resource.</p></li>
<li><p><strong>acl</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – Canned ACL applied on bucket creation (<code class="docutils literal notranslate"><span class="pre">private</span></code> or <code class="docutils literal notranslate"><span class="pre">public-read</span></code>)</p></li>
<li><p><strong>bucket_domain_name</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – The FQDN of the bucket (e.g. bucket-name.nyc3.digitaloceanspaces.com)</p></li>
<li><p><strong>cors_rules</strong> (<em>pulumi.Input</em><em>[</em><em>list</em><em>]</em>) – A rule of Cross-Origin Resource Sharing (documented below).</p></li>
<li><p><strong>force_destroy</strong> (<em>pulumi.Input</em><em>[</em><em>bool</em><em>]</em>) – Unless <code class="docutils literal notranslate"><span class="pre">true</span></code>, the bucket will only be destroyed if empty (Defaults to <code class="docutils literal notranslate"><span class="pre">false</span></code>)</p></li>
<li><p><strong>lifecycle_rules</strong> (<em>pulumi.Input</em><em>[</em><em>list</em><em>]</em>) – A configuration of object lifecycle management (documented below).</p></li>
<li><p><strong>name</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – The name of the bucket</p></li>
<li><p><strong>region</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – The region where the bucket resides (Defaults to <code class="docutils literal notranslate"><span class="pre">nyc3</span></code>)</p></li>
<li><p><strong>urn</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – The uniform resource name for the bucket</p></li>
<li><p><strong>versioning</strong> (<em>pulumi.Input</em><em>[</em><em>dict</em><em>]</em>) – A state of versioning (documented below)</p></li>
</ul>
</dd>
</dl>
<p>The <strong>cors_rules</strong> object supports the following:</p>
<ul class="simple">
<li><p><code class="docutils literal notranslate"><span class="pre">allowedHeaders</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[list]</span></code>) - A list of headers that will be included in the CORS preflight request’s <code class="docutils literal notranslate"><span class="pre">Access-Control-Request-Headers</span></code>. A header may contain one wildcard (e.g. <code class="docutils literal notranslate"><span class="pre">x-amz-*</span></code>).</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">allowedMethods</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[list]</span></code>) - A list of HTTP methods (e.g. <code class="docutils literal notranslate"><span class="pre">GET</span></code>) which are allowed from the specified origin.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">allowedOrigins</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[list]</span></code>) - A list of hosts from which requests using the specified methods are allowed. A host may contain one wildcard (e.g. <a class="reference external" href="http://">http://</a><a href="#id17"><span class="problematic" id="id18">*</span></a>.example.com).</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">maxAgeSeconds</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[float]</span></code>) - The time in seconds that browser can cache the response for a preflight request.</p></li>
</ul>
<p>The <strong>lifecycle_rules</strong> object supports the following:</p>
<ul class="simple">
<li><p><code class="docutils literal notranslate"><span class="pre">abortIncompleteMultipartUploadDays</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[float]</span></code>) - Specifies the number of days after initiating a multipart
upload when the multipart upload must be completed or else Spaces will abort the upload.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">enabled</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[bool]</span></code>) - Specifies lifecycle rule status.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">expiration</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[dict]</span></code>) - Specifies a time period after which applicable objects expire (documented below).</p>
<ul>
<li><p><code class="docutils literal notranslate"><span class="pre">date</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[str]</span></code>) - Specifies the date/time after which you want applicable objects to expire. The argument uses
RFC3339 format, e.g. “2020-03-22T15:03:55Z” or parts thereof e.g. “2019-02-28”.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">days</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[float]</span></code>) - Specifies the number of days after object creation when the applicable objects will expire.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">expiredObjectDeleteMarker</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[bool]</span></code>) - On a versioned bucket (versioning-enabled or versioning-suspended
bucket), setting this to true directs Spaces to delete expired object delete markers.</p></li>
</ul>
</li>
<li><p><code class="docutils literal notranslate"><span class="pre">id</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[str]</span></code>) - Unique identifier for the rule.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">noncurrentVersionExpiration</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[dict]</span></code>) - Specifies when non-current object versions expire (documented below).</p>
<ul>
<li><p><code class="docutils literal notranslate"><span class="pre">days</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[float]</span></code>) - Specifies the number of days after which an object’s non-current versions expire.</p></li>
</ul>
</li>
<li><p><code class="docutils literal notranslate"><span class="pre">prefix</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[str]</span></code>) - Object key prefix identifying one or more objects to which the rule applies.</p></li>
</ul>
<p>The <strong>versioning</strong> object supports the following:</p>
<ul class="simple">
<li><p><code class="docutils literal notranslate"><span class="pre">enabled</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[bool]</span></code>) - Enable versioning. Once you version-enable a bucket, it can never return to an unversioned
state. You can, however, suspend versioning on that bucket.</p></li>
</ul>
</dd></dl>

<dl class="py method">
<dt id="pulumi_digitalocean.SpacesBucket.translate_output_property">
<code class="sig-name descname">translate_output_property</code><span class="sig-paren">(</span><em class="sig-param"><span class="n">prop</span></em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_digitalocean.SpacesBucket.translate_output_property" title="Permalink to this definition">¶</a></dt>
<dd><p>Provides subclasses of Resource an opportunity to translate names of output properties
into a format of their choosing before writing those properties to the resource object.</p>
<dl class="field-list simple">
<dt class="field-odd">Parameters</dt>
<dd class="field-odd"><p><strong>prop</strong> (<em>str</em>) – A property name.</p>
</dd>
<dt class="field-even">Returns</dt>
<dd class="field-even"><p>A potentially transformed property name.</p>
</dd>
<dt class="field-odd">Return type</dt>
<dd class="field-odd"><p>str</p>
</dd>
</dl>
</dd></dl>

<dl class="py method">
<dt id="pulumi_digitalocean.SpacesBucket.translate_input_property">
<code class="sig-name descname">translate_input_property</code><span class="sig-paren">(</span><em class="sig-param"><span class="n">prop</span></em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_digitalocean.SpacesBucket.translate_input_property" title="Permalink to this definition">¶</a></dt>
<dd><p>Provides subclasses of Resource an opportunity to translate names of input properties into
a format of their choosing before sending those properties to the Pulumi engine.</p>
<dl class="field-list simple">
<dt class="field-odd">Parameters</dt>
<dd class="field-odd"><p><strong>prop</strong> (<em>str</em>) – A property name.</p>
</dd>
<dt class="field-even">Returns</dt>
<dd class="field-even"><p>A potentially transformed property name.</p>
</dd>
<dt class="field-odd">Return type</dt>
<dd class="field-odd"><p>str</p>
</dd>
</dl>
</dd></dl>

</dd></dl>

<dl class="py class">
<dt id="pulumi_digitalocean.SpacesBucketObject">
<em class="property">class </em><code class="sig-prename descclassname">pulumi_digitalocean.</code><code class="sig-name descname">SpacesBucketObject</code><span class="sig-paren">(</span><em class="sig-param"><span class="n">resource_name</span></em>, <em class="sig-param"><span class="n">opts</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">acl</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">bucket</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">cache_control</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">content</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">content_base64</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">content_disposition</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">content_encoding</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">content_language</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">content_type</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">etag</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">force_destroy</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">key</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">metadata</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">region</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">source</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">website_redirect</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">__props__</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">__name__</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">__opts__</span><span class="o">=</span><span class="default_value">None</span></em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_digitalocean.SpacesBucketObject" title="Permalink to this definition">¶</a></dt>
<dd><p>Create a SpacesBucketObject resource with the given unique name, props, and options.
:param str resource_name: The name of the resource.
:param pulumi.ResourceOptions opts: Options for the resource.
:param pulumi.Input[str] acl: The canned ACL to apply. DigitalOcean supports “private” and “public-read”. (Defaults to “private”.)
:param pulumi.Input[str] bucket: The name of the bucket to put the file in.
:param pulumi.Input[str] cache_control: Specifies caching behavior along the request/reply chain Read <a class="reference external" href="http://www.w3.org/Protocols/rfc2616/rfc2616-sec14.html#sec14.9">w3c cache_control</a> for further details.
:param pulumi.Input[str] content: Literal string value to use as the object content, which will be uploaded as UTF-8-encoded text.
:param pulumi.Input[str] content_base64: Base64-encoded data that will be decoded and uploaded as raw bytes for the object content. This allows safely uploading non-UTF8 binary data, but is recommended only for small content such as the result of the <code class="docutils literal notranslate"><span class="pre">gzipbase64</span></code> function with small text strings. For larger objects, use <code class="docutils literal notranslate"><span class="pre">source</span></code> to stream the content from a disk file.
:param pulumi.Input[str] content_disposition: Specifies presentational information for the object. Read <a class="reference external" href="http://www.w3.org/Protocols/rfc2616/rfc2616-sec19.html#sec19.5.1">w3c content_disposition</a> for further information.
:param pulumi.Input[str] content_encoding: Specifies what content encodings have been applied to the object and thus what decoding mechanisms must be applied to obtain the media-type referenced by the Content-Type header field. Read <a class="reference external" href="http://www.w3.org/Protocols/rfc2616/rfc2616-sec14.html#sec14.11">w3c content encoding</a> for further information.
:param pulumi.Input[str] content_language: The language the content is in e.g. en-US or en-GB.
:param pulumi.Input[str] content_type: A standard MIME type describing the format of the object data, e.g. application/octet-stream. All Valid MIME Types are valid for this input.
:param pulumi.Input[str] etag: the ETag generated for the object (an MD5 sum of the object content). The hash is an MD5 digest of the</p>
<blockquote>
<div><p>object data. For objects created by either the Multipart Upload or Part Copy operation, the hash is not an MD5
digest. More information on possible values can be found on <a class="reference external" href="https://docs.aws.amazon.com/AmazonS3/latest/API/RESTCommonResponseHeaders.html">Common Response Headers</a>.</p>
</div></blockquote>
<dl class="field-list simple">
<dt class="field-odd">Parameters</dt>
<dd class="field-odd"><ul class="simple">
<li><p><strong>force_destroy</strong> (<em>pulumi.Input</em><em>[</em><em>bool</em><em>]</em>) – Allow the object to be deleted by removing any legal hold on any object version.
Default is <code class="docutils literal notranslate"><span class="pre">false</span></code>. This value should be set to <code class="docutils literal notranslate"><span class="pre">true</span></code> only if the bucket has S3 object lock enabled.</p></li>
<li><p><strong>key</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – The name of the object once it is in the bucket.</p></li>
<li><p><strong>metadata</strong> (<em>pulumi.Input</em><em>[</em><em>dict</em><em>]</em>) – A mapping of keys/values to provision metadata (will be automatically prefixed by <code class="docutils literal notranslate"><span class="pre">x-amz-meta-</span></code>, note that only lowercase label are currently supported by the AWS Go API).</p></li>
<li><p><strong>region</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – The region where the bucket resides (Defaults to <code class="docutils literal notranslate"><span class="pre">nyc3</span></code>)</p></li>
<li><p><strong>source</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – The path to a file that will be read and uploaded as raw bytes for the object content.</p></li>
<li><p><strong>website_redirect</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – Specifies a target URL for <a class="reference external" href="http://docs.aws.amazon.com/AmazonS3/latest/dev/how-to-page-redirect.html">website redirect</a>.</p></li>
</ul>
</dd>
</dl>
<dl class="py attribute">
<dt id="pulumi_digitalocean.SpacesBucketObject.acl">
<code class="sig-name descname">acl</code><em class="property">: pulumi.Output[str]</em><em class="property"> = None</em><a class="headerlink" href="#pulumi_digitalocean.SpacesBucketObject.acl" title="Permalink to this definition">¶</a></dt>
<dd><p>The canned ACL to apply. DigitalOcean supports “private” and “public-read”. (Defaults to “private”.)</p>
</dd></dl>

<dl class="py attribute">
<dt id="pulumi_digitalocean.SpacesBucketObject.bucket">
<code class="sig-name descname">bucket</code><em class="property">: pulumi.Output[str]</em><em class="property"> = None</em><a class="headerlink" href="#pulumi_digitalocean.SpacesBucketObject.bucket" title="Permalink to this definition">¶</a></dt>
<dd><p>The name of the bucket to put the file in.</p>
</dd></dl>

<dl class="py attribute">
<dt id="pulumi_digitalocean.SpacesBucketObject.cache_control">
<code class="sig-name descname">cache_control</code><em class="property">: pulumi.Output[str]</em><em class="property"> = None</em><a class="headerlink" href="#pulumi_digitalocean.SpacesBucketObject.cache_control" title="Permalink to this definition">¶</a></dt>
<dd><p>Specifies caching behavior along the request/reply chain Read <a class="reference external" href="http://www.w3.org/Protocols/rfc2616/rfc2616-sec14.html#sec14.9">w3c cache_control</a> for further details.</p>
</dd></dl>

<dl class="py attribute">
<dt id="pulumi_digitalocean.SpacesBucketObject.content">
<code class="sig-name descname">content</code><em class="property">: pulumi.Output[str]</em><em class="property"> = None</em><a class="headerlink" href="#pulumi_digitalocean.SpacesBucketObject.content" title="Permalink to this definition">¶</a></dt>
<dd><p>Literal string value to use as the object content, which will be uploaded as UTF-8-encoded text.</p>
</dd></dl>

<dl class="py attribute">
<dt id="pulumi_digitalocean.SpacesBucketObject.content_base64">
<code class="sig-name descname">content_base64</code><em class="property">: pulumi.Output[str]</em><em class="property"> = None</em><a class="headerlink" href="#pulumi_digitalocean.SpacesBucketObject.content_base64" title="Permalink to this definition">¶</a></dt>
<dd><p>Base64-encoded data that will be decoded and uploaded as raw bytes for the object content. This allows safely uploading non-UTF8 binary data, but is recommended only for small content such as the result of the <code class="docutils literal notranslate"><span class="pre">gzipbase64</span></code> function with small text strings. For larger objects, use <code class="docutils literal notranslate"><span class="pre">source</span></code> to stream the content from a disk file.</p>
</dd></dl>

<dl class="py attribute">
<dt id="pulumi_digitalocean.SpacesBucketObject.content_disposition">
<code class="sig-name descname">content_disposition</code><em class="property">: pulumi.Output[str]</em><em class="property"> = None</em><a class="headerlink" href="#pulumi_digitalocean.SpacesBucketObject.content_disposition" title="Permalink to this definition">¶</a></dt>
<dd><p>Specifies presentational information for the object. Read <a class="reference external" href="http://www.w3.org/Protocols/rfc2616/rfc2616-sec19.html#sec19.5.1">w3c content_disposition</a> for further information.</p>
</dd></dl>

<dl class="py attribute">
<dt id="pulumi_digitalocean.SpacesBucketObject.content_encoding">
<code class="sig-name descname">content_encoding</code><em class="property">: pulumi.Output[str]</em><em class="property"> = None</em><a class="headerlink" href="#pulumi_digitalocean.SpacesBucketObject.content_encoding" title="Permalink to this definition">¶</a></dt>
<dd><p>Specifies what content encodings have been applied to the object and thus what decoding mechanisms must be applied to obtain the media-type referenced by the Content-Type header field. Read <a class="reference external" href="http://www.w3.org/Protocols/rfc2616/rfc2616-sec14.html#sec14.11">w3c content encoding</a> for further information.</p>
</dd></dl>

<dl class="py attribute">
<dt id="pulumi_digitalocean.SpacesBucketObject.content_language">
<code class="sig-name descname">content_language</code><em class="property">: pulumi.Output[str]</em><em class="property"> = None</em><a class="headerlink" href="#pulumi_digitalocean.SpacesBucketObject.content_language" title="Permalink to this definition">¶</a></dt>
<dd><p>The language the content is in e.g. en-US or en-GB.</p>
</dd></dl>

<dl class="py attribute">
<dt id="pulumi_digitalocean.SpacesBucketObject.content_type">
<code class="sig-name descname">content_type</code><em class="property">: pulumi.Output[str]</em><em class="property"> = None</em><a class="headerlink" href="#pulumi_digitalocean.SpacesBucketObject.content_type" title="Permalink to this definition">¶</a></dt>
<dd><p>A standard MIME type describing the format of the object data, e.g. application/octet-stream. All Valid MIME Types are valid for this input.</p>
</dd></dl>

<dl class="py attribute">
<dt id="pulumi_digitalocean.SpacesBucketObject.etag">
<code class="sig-name descname">etag</code><em class="property">: pulumi.Output[str]</em><em class="property"> = None</em><a class="headerlink" href="#pulumi_digitalocean.SpacesBucketObject.etag" title="Permalink to this definition">¶</a></dt>
<dd><p>the ETag generated for the object (an MD5 sum of the object content). The hash is an MD5 digest of the
object data. For objects created by either the Multipart Upload or Part Copy operation, the hash is not an MD5
digest. More information on possible values can be found on <a class="reference external" href="https://docs.aws.amazon.com/AmazonS3/latest/API/RESTCommonResponseHeaders.html">Common Response Headers</a>.</p>
</dd></dl>

<dl class="py attribute">
<dt id="pulumi_digitalocean.SpacesBucketObject.force_destroy">
<code class="sig-name descname">force_destroy</code><em class="property">: pulumi.Output[bool]</em><em class="property"> = None</em><a class="headerlink" href="#pulumi_digitalocean.SpacesBucketObject.force_destroy" title="Permalink to this definition">¶</a></dt>
<dd><p>Allow the object to be deleted by removing any legal hold on any object version.
Default is <code class="docutils literal notranslate"><span class="pre">false</span></code>. This value should be set to <code class="docutils literal notranslate"><span class="pre">true</span></code> only if the bucket has S3 object lock enabled.</p>
</dd></dl>

<dl class="py attribute">
<dt id="pulumi_digitalocean.SpacesBucketObject.key">
<code class="sig-name descname">key</code><em class="property">: pulumi.Output[str]</em><em class="property"> = None</em><a class="headerlink" href="#pulumi_digitalocean.SpacesBucketObject.key" title="Permalink to this definition">¶</a></dt>
<dd><p>The name of the object once it is in the bucket.</p>
</dd></dl>

<dl class="py attribute">
<dt id="pulumi_digitalocean.SpacesBucketObject.metadata">
<code class="sig-name descname">metadata</code><em class="property">: pulumi.Output[dict]</em><em class="property"> = None</em><a class="headerlink" href="#pulumi_digitalocean.SpacesBucketObject.metadata" title="Permalink to this definition">¶</a></dt>
<dd><p>A mapping of keys/values to provision metadata (will be automatically prefixed by <code class="docutils literal notranslate"><span class="pre">x-amz-meta-</span></code>, note that only lowercase label are currently supported by the AWS Go API).</p>
</dd></dl>

<dl class="py attribute">
<dt id="pulumi_digitalocean.SpacesBucketObject.region">
<code class="sig-name descname">region</code><em class="property">: pulumi.Output[str]</em><em class="property"> = None</em><a class="headerlink" href="#pulumi_digitalocean.SpacesBucketObject.region" title="Permalink to this definition">¶</a></dt>
<dd><p>The region where the bucket resides (Defaults to <code class="docutils literal notranslate"><span class="pre">nyc3</span></code>)</p>
</dd></dl>

<dl class="py attribute">
<dt id="pulumi_digitalocean.SpacesBucketObject.source">
<code class="sig-name descname">source</code><em class="property">: pulumi.Output[str]</em><em class="property"> = None</em><a class="headerlink" href="#pulumi_digitalocean.SpacesBucketObject.source" title="Permalink to this definition">¶</a></dt>
<dd><p>The path to a file that will be read and uploaded as raw bytes for the object content.</p>
</dd></dl>

<dl class="py attribute">
<dt id="pulumi_digitalocean.SpacesBucketObject.version_id">
<code class="sig-name descname">version_id</code><em class="property">: pulumi.Output[str]</em><em class="property"> = None</em><a class="headerlink" href="#pulumi_digitalocean.SpacesBucketObject.version_id" title="Permalink to this definition">¶</a></dt>
<dd><p>A unique version ID value for the object, if bucket versioning is enabled.</p>
</dd></dl>

<dl class="py attribute">
<dt id="pulumi_digitalocean.SpacesBucketObject.website_redirect">
<code class="sig-name descname">website_redirect</code><em class="property">: pulumi.Output[str]</em><em class="property"> = None</em><a class="headerlink" href="#pulumi_digitalocean.SpacesBucketObject.website_redirect" title="Permalink to this definition">¶</a></dt>
<dd><p>Specifies a target URL for <a class="reference external" href="http://docs.aws.amazon.com/AmazonS3/latest/dev/how-to-page-redirect.html">website redirect</a>.</p>
</dd></dl>

<dl class="py method">
<dt id="pulumi_digitalocean.SpacesBucketObject.get">
<em class="property">static </em><code class="sig-name descname">get</code><span class="sig-paren">(</span><em class="sig-param"><span class="n">resource_name</span></em>, <em class="sig-param"><span class="n">id</span></em>, <em class="sig-param"><span class="n">opts</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">acl</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">bucket</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">cache_control</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">content</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">content_base64</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">content_disposition</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">content_encoding</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">content_language</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">content_type</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">etag</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">force_destroy</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">key</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">metadata</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">region</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">source</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">version_id</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">website_redirect</span><span class="o">=</span><span class="default_value">None</span></em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_digitalocean.SpacesBucketObject.get" title="Permalink to this definition">¶</a></dt>
<dd><p>Get an existing SpacesBucketObject resource’s state with the given name, id, and optional extra
properties used to qualify the lookup.</p>
<dl class="field-list simple">
<dt class="field-odd">Parameters</dt>
<dd class="field-odd"><ul class="simple">
<li><p><strong>resource_name</strong> (<em>str</em>) – The unique name of the resulting resource.</p></li>
<li><p><strong>id</strong> (<em>str</em>) – The unique provider ID of the resource to lookup.</p></li>
<li><p><strong>opts</strong> (<a class="reference internal" href="../pulumi/#pulumi.ResourceOptions" title="pulumi.ResourceOptions"><em>pulumi.ResourceOptions</em></a>) – Options for the resource.</p></li>
<li><p><strong>acl</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – The canned ACL to apply. DigitalOcean supports “private” and “public-read”. (Defaults to “private”.)</p></li>
<li><p><strong>bucket</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – The name of the bucket to put the file in.</p></li>
<li><p><strong>cache_control</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – <p>Specifies caching behavior along the request/reply chain Read <a class="reference external" href="http://www.w3.org/Protocols/rfc2616/rfc2616-sec14.html#sec14.9">w3c cache_control</a> for further details.</p>
</p></li>
<li><p><strong>content</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – Literal string value to use as the object content, which will be uploaded as UTF-8-encoded text.</p></li>
<li><p><strong>content_base64</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – Base64-encoded data that will be decoded and uploaded as raw bytes for the object content. This allows safely uploading non-UTF8 binary data, but is recommended only for small content such as the result of the <code class="docutils literal notranslate"><span class="pre">gzipbase64</span></code> function with small text strings. For larger objects, use <code class="docutils literal notranslate"><span class="pre">source</span></code> to stream the content from a disk file.</p></li>
<li><p><strong>content_disposition</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – <p>Specifies presentational information for the object. Read <a class="reference external" href="http://www.w3.org/Protocols/rfc2616/rfc2616-sec19.html#sec19.5.1">w3c content_disposition</a> for further information.</p>
</p></li>
<li><p><strong>content_encoding</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – <p>Specifies what content encodings have been applied to the object and thus what decoding mechanisms must be applied to obtain the media-type referenced by the Content-Type header field. Read <a class="reference external" href="http://www.w3.org/Protocols/rfc2616/rfc2616-sec14.html#sec14.11">w3c content encoding</a> for further information.</p>
</p></li>
<li><p><strong>content_language</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – The language the content is in e.g. en-US or en-GB.</p></li>
<li><p><strong>content_type</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – A standard MIME type describing the format of the object data, e.g. application/octet-stream. All Valid MIME Types are valid for this input.</p></li>
<li><p><strong>etag</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – <p>the ETag generated for the object (an MD5 sum of the object content). The hash is an MD5 digest of the
object data. For objects created by either the Multipart Upload or Part Copy operation, the hash is not an MD5
digest. More information on possible values can be found on <a class="reference external" href="https://docs.aws.amazon.com/AmazonS3/latest/API/RESTCommonResponseHeaders.html">Common Response Headers</a>.</p>
</p></li>
<li><p><strong>force_destroy</strong> (<em>pulumi.Input</em><em>[</em><em>bool</em><em>]</em>) – Allow the object to be deleted by removing any legal hold on any object version.
Default is <code class="docutils literal notranslate"><span class="pre">false</span></code>. This value should be set to <code class="docutils literal notranslate"><span class="pre">true</span></code> only if the bucket has S3 object lock enabled.</p></li>
<li><p><strong>key</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – The name of the object once it is in the bucket.</p></li>
<li><p><strong>metadata</strong> (<em>pulumi.Input</em><em>[</em><em>dict</em><em>]</em>) – A mapping of keys/values to provision metadata (will be automatically prefixed by <code class="docutils literal notranslate"><span class="pre">x-amz-meta-</span></code>, note that only lowercase label are currently supported by the AWS Go API).</p></li>
<li><p><strong>region</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – The region where the bucket resides (Defaults to <code class="docutils literal notranslate"><span class="pre">nyc3</span></code>)</p></li>
<li><p><strong>source</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – The path to a file that will be read and uploaded as raw bytes for the object content.</p></li>
<li><p><strong>version_id</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – A unique version ID value for the object, if bucket versioning is enabled.</p></li>
<li><p><strong>website_redirect</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – <p>Specifies a target URL for <a class="reference external" href="http://docs.aws.amazon.com/AmazonS3/latest/dev/how-to-page-redirect.html">website redirect</a>.</p>
</p></li>
</ul>
</dd>
</dl>
</dd></dl>

<dl class="py method">
<dt id="pulumi_digitalocean.SpacesBucketObject.translate_output_property">
<code class="sig-name descname">translate_output_property</code><span class="sig-paren">(</span><em class="sig-param"><span class="n">prop</span></em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_digitalocean.SpacesBucketObject.translate_output_property" title="Permalink to this definition">¶</a></dt>
<dd><p>Provides subclasses of Resource an opportunity to translate names of output properties
into a format of their choosing before writing those properties to the resource object.</p>
<dl class="field-list simple">
<dt class="field-odd">Parameters</dt>
<dd class="field-odd"><p><strong>prop</strong> (<em>str</em>) – A property name.</p>
</dd>
<dt class="field-even">Returns</dt>
<dd class="field-even"><p>A potentially transformed property name.</p>
</dd>
<dt class="field-odd">Return type</dt>
<dd class="field-odd"><p>str</p>
</dd>
</dl>
</dd></dl>

<dl class="py method">
<dt id="pulumi_digitalocean.SpacesBucketObject.translate_input_property">
<code class="sig-name descname">translate_input_property</code><span class="sig-paren">(</span><em class="sig-param"><span class="n">prop</span></em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_digitalocean.SpacesBucketObject.translate_input_property" title="Permalink to this definition">¶</a></dt>
<dd><p>Provides subclasses of Resource an opportunity to translate names of input properties into
a format of their choosing before sending those properties to the Pulumi engine.</p>
<dl class="field-list simple">
<dt class="field-odd">Parameters</dt>
<dd class="field-odd"><p><strong>prop</strong> (<em>str</em>) – A property name.</p>
</dd>
<dt class="field-even">Returns</dt>
<dd class="field-even"><p>A potentially transformed property name.</p>
</dd>
<dt class="field-odd">Return type</dt>
<dd class="field-odd"><p>str</p>
</dd>
</dl>
</dd></dl>

</dd></dl>

<dl class="py class">
<dt id="pulumi_digitalocean.SshKey">
<em class="property">class </em><code class="sig-prename descclassname">pulumi_digitalocean.</code><code class="sig-name descname">SshKey</code><span class="sig-paren">(</span><em class="sig-param"><span class="n">resource_name</span></em>, <em class="sig-param"><span class="n">opts</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">name</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">public_key</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">__props__</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">__name__</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">__opts__</span><span class="o">=</span><span class="default_value">None</span></em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_digitalocean.SshKey" title="Permalink to this definition">¶</a></dt>
<dd><p>Create a SshKey resource with the given unique name, props, and options.
:param str resource_name: The name of the resource.
:param pulumi.ResourceOptions opts: Options for the resource.
:param pulumi.Input[str] name: The name of the SSH key for identification
:param pulumi.Input[str] public_key: The public key. If this is a file, it</p>
<blockquote>
<div><p>can be read using the file interpolation function</p>
</div></blockquote>
<dl class="py attribute">
<dt id="pulumi_digitalocean.SshKey.fingerprint">
<code class="sig-name descname">fingerprint</code><em class="property">: pulumi.Output[str]</em><em class="property"> = None</em><a class="headerlink" href="#pulumi_digitalocean.SshKey.fingerprint" title="Permalink to this definition">¶</a></dt>
<dd><p>The fingerprint of the SSH key</p>
</dd></dl>

<dl class="py attribute">
<dt id="pulumi_digitalocean.SshKey.name">
<code class="sig-name descname">name</code><em class="property">: pulumi.Output[str]</em><em class="property"> = None</em><a class="headerlink" href="#pulumi_digitalocean.SshKey.name" title="Permalink to this definition">¶</a></dt>
<dd><p>The name of the SSH key for identification</p>
</dd></dl>

<dl class="py attribute">
<dt id="pulumi_digitalocean.SshKey.public_key">
<code class="sig-name descname">public_key</code><em class="property">: pulumi.Output[str]</em><em class="property"> = None</em><a class="headerlink" href="#pulumi_digitalocean.SshKey.public_key" title="Permalink to this definition">¶</a></dt>
<dd><p>The public key. If this is a file, it
can be read using the file interpolation function</p>
</dd></dl>

<dl class="py method">
<dt id="pulumi_digitalocean.SshKey.get">
<em class="property">static </em><code class="sig-name descname">get</code><span class="sig-paren">(</span><em class="sig-param"><span class="n">resource_name</span></em>, <em class="sig-param"><span class="n">id</span></em>, <em class="sig-param"><span class="n">opts</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">fingerprint</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">name</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">public_key</span><span class="o">=</span><span class="default_value">None</span></em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_digitalocean.SshKey.get" title="Permalink to this definition">¶</a></dt>
<dd><p>Get an existing SshKey resource’s state with the given name, id, and optional extra
properties used to qualify the lookup.</p>
<dl class="field-list simple">
<dt class="field-odd">Parameters</dt>
<dd class="field-odd"><ul class="simple">
<li><p><strong>resource_name</strong> (<em>str</em>) – The unique name of the resulting resource.</p></li>
<li><p><strong>id</strong> (<em>str</em>) – The unique provider ID of the resource to lookup.</p></li>
<li><p><strong>opts</strong> (<a class="reference internal" href="../pulumi/#pulumi.ResourceOptions" title="pulumi.ResourceOptions"><em>pulumi.ResourceOptions</em></a>) – Options for the resource.</p></li>
<li><p><strong>fingerprint</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – The fingerprint of the SSH key</p></li>
<li><p><strong>name</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – The name of the SSH key for identification</p></li>
<li><p><strong>public_key</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – The public key. If this is a file, it
can be read using the file interpolation function</p></li>
</ul>
</dd>
</dl>
</dd></dl>

<dl class="py method">
<dt id="pulumi_digitalocean.SshKey.translate_output_property">
<code class="sig-name descname">translate_output_property</code><span class="sig-paren">(</span><em class="sig-param"><span class="n">prop</span></em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_digitalocean.SshKey.translate_output_property" title="Permalink to this definition">¶</a></dt>
<dd><p>Provides subclasses of Resource an opportunity to translate names of output properties
into a format of their choosing before writing those properties to the resource object.</p>
<dl class="field-list simple">
<dt class="field-odd">Parameters</dt>
<dd class="field-odd"><p><strong>prop</strong> (<em>str</em>) – A property name.</p>
</dd>
<dt class="field-even">Returns</dt>
<dd class="field-even"><p>A potentially transformed property name.</p>
</dd>
<dt class="field-odd">Return type</dt>
<dd class="field-odd"><p>str</p>
</dd>
</dl>
</dd></dl>

<dl class="py method">
<dt id="pulumi_digitalocean.SshKey.translate_input_property">
<code class="sig-name descname">translate_input_property</code><span class="sig-paren">(</span><em class="sig-param"><span class="n">prop</span></em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_digitalocean.SshKey.translate_input_property" title="Permalink to this definition">¶</a></dt>
<dd><p>Provides subclasses of Resource an opportunity to translate names of input properties into
a format of their choosing before sending those properties to the Pulumi engine.</p>
<dl class="field-list simple">
<dt class="field-odd">Parameters</dt>
<dd class="field-odd"><p><strong>prop</strong> (<em>str</em>) – A property name.</p>
</dd>
<dt class="field-even">Returns</dt>
<dd class="field-even"><p>A potentially transformed property name.</p>
</dd>
<dt class="field-odd">Return type</dt>
<dd class="field-odd"><p>str</p>
</dd>
</dl>
</dd></dl>

</dd></dl>

<dl class="py class">
<dt id="pulumi_digitalocean.Tag">
<em class="property">class </em><code class="sig-prename descclassname">pulumi_digitalocean.</code><code class="sig-name descname">Tag</code><span class="sig-paren">(</span><em class="sig-param"><span class="n">resource_name</span></em>, <em class="sig-param"><span class="n">opts</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">name</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">__props__</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">__name__</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">__opts__</span><span class="o">=</span><span class="default_value">None</span></em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_digitalocean.Tag" title="Permalink to this definition">¶</a></dt>
<dd><p>Provides a DigitalOcean Tag resource. A Tag is a label that can be applied to a
Droplet resource in order to better organize or facilitate the lookups and
actions on it. Tags created with this resource can be referenced in your Droplet
configuration via their ID or name.</p>
<div class="highlight-python notranslate"><div class="highlight"><pre><span></span><span class="kn">import</span> <span class="nn">pulumi</span>
<span class="kn">import</span> <span class="nn">pulumi_digitalocean</span> <span class="k">as</span> <span class="nn">digitalocean</span>

<span class="c1"># Create a new tag</span>
<span class="n">foobar</span> <span class="o">=</span> <span class="n">digitalocean</span><span class="o">.</span><span class="n">Tag</span><span class="p">(</span><span class="s2">&quot;foobar&quot;</span><span class="p">)</span>
<span class="c1"># Create a new Droplet in nyc3 with the foobar tag</span>
<span class="n">web</span> <span class="o">=</span> <span class="n">digitalocean</span><span class="o">.</span><span class="n">Droplet</span><span class="p">(</span><span class="s2">&quot;web&quot;</span><span class="p">,</span>
    <span class="n">image</span><span class="o">=</span><span class="s2">&quot;ubuntu-18-04-x64&quot;</span><span class="p">,</span>
    <span class="n">region</span><span class="o">=</span><span class="s2">&quot;nyc3&quot;</span><span class="p">,</span>
    <span class="n">size</span><span class="o">=</span><span class="s2">&quot;s-1vcpu-1gb&quot;</span><span class="p">,</span>
    <span class="n">tags</span><span class="o">=</span><span class="p">[</span><span class="n">foobar</span><span class="o">.</span><span class="n">id</span><span class="p">])</span>
</pre></div>
</div>
<dl class="field-list simple">
<dt class="field-odd">Parameters</dt>
<dd class="field-odd"><ul class="simple">
<li><p><strong>resource_name</strong> (<em>str</em>) – The name of the resource.</p></li>
<li><p><strong>opts</strong> (<a class="reference internal" href="../pulumi/#pulumi.ResourceOptions" title="pulumi.ResourceOptions"><em>pulumi.ResourceOptions</em></a>) – Options for the resource.</p></li>
<li><p><strong>name</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – The name of the tag</p></li>
</ul>
</dd>
</dl>
<dl class="py attribute">
<dt id="pulumi_digitalocean.Tag.name">
<code class="sig-name descname">name</code><em class="property">: pulumi.Output[str]</em><em class="property"> = None</em><a class="headerlink" href="#pulumi_digitalocean.Tag.name" title="Permalink to this definition">¶</a></dt>
<dd><p>The name of the tag</p>
</dd></dl>

<dl class="py method">
<dt id="pulumi_digitalocean.Tag.get">
<em class="property">static </em><code class="sig-name descname">get</code><span class="sig-paren">(</span><em class="sig-param"><span class="n">resource_name</span></em>, <em class="sig-param"><span class="n">id</span></em>, <em class="sig-param"><span class="n">opts</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">name</span><span class="o">=</span><span class="default_value">None</span></em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_digitalocean.Tag.get" title="Permalink to this definition">¶</a></dt>
<dd><p>Get an existing Tag resource’s state with the given name, id, and optional extra
properties used to qualify the lookup.</p>
<dl class="field-list simple">
<dt class="field-odd">Parameters</dt>
<dd class="field-odd"><ul class="simple">
<li><p><strong>resource_name</strong> (<em>str</em>) – The unique name of the resulting resource.</p></li>
<li><p><strong>id</strong> (<em>str</em>) – The unique provider ID of the resource to lookup.</p></li>
<li><p><strong>opts</strong> (<a class="reference internal" href="../pulumi/#pulumi.ResourceOptions" title="pulumi.ResourceOptions"><em>pulumi.ResourceOptions</em></a>) – Options for the resource.</p></li>
<li><p><strong>name</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – The name of the tag</p></li>
</ul>
</dd>
</dl>
</dd></dl>

<dl class="py method">
<dt id="pulumi_digitalocean.Tag.translate_output_property">
<code class="sig-name descname">translate_output_property</code><span class="sig-paren">(</span><em class="sig-param"><span class="n">prop</span></em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_digitalocean.Tag.translate_output_property" title="Permalink to this definition">¶</a></dt>
<dd><p>Provides subclasses of Resource an opportunity to translate names of output properties
into a format of their choosing before writing those properties to the resource object.</p>
<dl class="field-list simple">
<dt class="field-odd">Parameters</dt>
<dd class="field-odd"><p><strong>prop</strong> (<em>str</em>) – A property name.</p>
</dd>
<dt class="field-even">Returns</dt>
<dd class="field-even"><p>A potentially transformed property name.</p>
</dd>
<dt class="field-odd">Return type</dt>
<dd class="field-odd"><p>str</p>
</dd>
</dl>
</dd></dl>

<dl class="py method">
<dt id="pulumi_digitalocean.Tag.translate_input_property">
<code class="sig-name descname">translate_input_property</code><span class="sig-paren">(</span><em class="sig-param"><span class="n">prop</span></em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_digitalocean.Tag.translate_input_property" title="Permalink to this definition">¶</a></dt>
<dd><p>Provides subclasses of Resource an opportunity to translate names of input properties into
a format of their choosing before sending those properties to the Pulumi engine.</p>
<dl class="field-list simple">
<dt class="field-odd">Parameters</dt>
<dd class="field-odd"><p><strong>prop</strong> (<em>str</em>) – A property name.</p>
</dd>
<dt class="field-even">Returns</dt>
<dd class="field-even"><p>A potentially transformed property name.</p>
</dd>
<dt class="field-odd">Return type</dt>
<dd class="field-odd"><p>str</p>
</dd>
</dl>
</dd></dl>

</dd></dl>

<dl class="py class">
<dt id="pulumi_digitalocean.Volume">
<em class="property">class </em><code class="sig-prename descclassname">pulumi_digitalocean.</code><code class="sig-name descname">Volume</code><span class="sig-paren">(</span><em class="sig-param"><span class="n">resource_name</span></em>, <em class="sig-param"><span class="n">opts</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">description</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">filesystem_type</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">initial_filesystem_label</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">initial_filesystem_type</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">name</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">region</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">size</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">snapshot_id</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">tags</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">__props__</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">__name__</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">__opts__</span><span class="o">=</span><span class="default_value">None</span></em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_digitalocean.Volume" title="Permalink to this definition">¶</a></dt>
<dd><p>Provides a DigitalOcean Block Storage volume which can be attached to a Droplet in order to provide expanded storage.</p>
<div class="highlight-python notranslate"><div class="highlight"><pre><span></span><span class="kn">import</span> <span class="nn">pulumi</span>
<span class="kn">import</span> <span class="nn">pulumi_digitalocean</span> <span class="k">as</span> <span class="nn">digitalocean</span>

<span class="n">foobar_volume</span> <span class="o">=</span> <span class="n">digitalocean</span><span class="o">.</span><span class="n">Volume</span><span class="p">(</span><span class="s2">&quot;foobarVolume&quot;</span><span class="p">,</span>
    <span class="n">region</span><span class="o">=</span><span class="s2">&quot;nyc1&quot;</span><span class="p">,</span>
    <span class="n">size</span><span class="o">=</span><span class="mi">100</span><span class="p">,</span>
    <span class="n">initial_filesystem_type</span><span class="o">=</span><span class="s2">&quot;ext4&quot;</span><span class="p">,</span>
    <span class="n">description</span><span class="o">=</span><span class="s2">&quot;an example volume&quot;</span><span class="p">)</span>
<span class="n">foobar_droplet</span> <span class="o">=</span> <span class="n">digitalocean</span><span class="o">.</span><span class="n">Droplet</span><span class="p">(</span><span class="s2">&quot;foobarDroplet&quot;</span><span class="p">,</span>
    <span class="n">size</span><span class="o">=</span><span class="s2">&quot;s-1vcpu-1gb&quot;</span><span class="p">,</span>
    <span class="n">image</span><span class="o">=</span><span class="s2">&quot;ubuntu-18-04-x64&quot;</span><span class="p">,</span>
    <span class="n">region</span><span class="o">=</span><span class="s2">&quot;nyc1&quot;</span><span class="p">)</span>
<span class="n">foobar_volume_attachment</span> <span class="o">=</span> <span class="n">digitalocean</span><span class="o">.</span><span class="n">VolumeAttachment</span><span class="p">(</span><span class="s2">&quot;foobarVolumeAttachment&quot;</span><span class="p">,</span>
    <span class="n">droplet_id</span><span class="o">=</span><span class="n">foobar_droplet</span><span class="o">.</span><span class="n">id</span><span class="p">,</span>
    <span class="n">volume_id</span><span class="o">=</span><span class="n">foobar_volume</span><span class="o">.</span><span class="n">id</span><span class="p">)</span>
</pre></div>
</div>
<dl class="field-list simple">
<dt class="field-odd">Parameters</dt>
<dd class="field-odd"><ul class="simple">
<li><p><strong>resource_name</strong> (<em>str</em>) – The name of the resource.</p></li>
<li><p><strong>opts</strong> (<a class="reference internal" href="../pulumi/#pulumi.ResourceOptions" title="pulumi.ResourceOptions"><em>pulumi.ResourceOptions</em></a>) – Options for the resource.</p></li>
<li><p><strong>description</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – A free-form text field up to a limit of 1024 bytes to describe a block storage volume.</p></li>
<li><p><strong>filesystem_type</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – Filesystem type (<code class="docutils literal notranslate"><span class="pre">xfs</span></code> or <code class="docutils literal notranslate"><span class="pre">ext4</span></code>) for the block storage volume.</p></li>
<li><p><strong>initial_filesystem_label</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – Initial filesystem label for the block storage volume.</p></li>
<li><p><strong>initial_filesystem_type</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – Initial filesystem type (<code class="docutils literal notranslate"><span class="pre">xfs</span></code> or <code class="docutils literal notranslate"><span class="pre">ext4</span></code>) for the block storage volume.</p></li>
<li><p><strong>name</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – A name for the block storage volume. Must be lowercase and be composed only of numbers, letters and “-“, up to a limit of 64 characters.</p></li>
<li><p><strong>region</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – The region that the block storage volume will be created in.</p></li>
<li><p><strong>size</strong> (<em>pulumi.Input</em><em>[</em><em>float</em><em>]</em>) – The size of the block storage volume in GiB. If updated, can only be expanded.</p></li>
<li><p><strong>snapshot_id</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – The ID of an existing volume snapshot from which the new volume will be created. If supplied, the region and size will be limitied on creation to that of the referenced snapshot</p></li>
<li><p><strong>tags</strong> (<em>pulumi.Input</em><em>[</em><em>list</em><em>]</em>) – A list of the tags to be applied to this Volume.</p></li>
</ul>
</dd>
</dl>
<dl class="py attribute">
<dt id="pulumi_digitalocean.Volume.description">
<code class="sig-name descname">description</code><em class="property">: pulumi.Output[str]</em><em class="property"> = None</em><a class="headerlink" href="#pulumi_digitalocean.Volume.description" title="Permalink to this definition">¶</a></dt>
<dd><p>A free-form text field up to a limit of 1024 bytes to describe a block storage volume.</p>
</dd></dl>

<dl class="py attribute">
<dt id="pulumi_digitalocean.Volume.droplet_ids">
<code class="sig-name descname">droplet_ids</code><em class="property">: pulumi.Output[list]</em><em class="property"> = None</em><a class="headerlink" href="#pulumi_digitalocean.Volume.droplet_ids" title="Permalink to this definition">¶</a></dt>
<dd><p>A list of associated droplet ids.</p>
</dd></dl>

<dl class="py attribute">
<dt id="pulumi_digitalocean.Volume.filesystem_label">
<code class="sig-name descname">filesystem_label</code><em class="property">: pulumi.Output[str]</em><em class="property"> = None</em><a class="headerlink" href="#pulumi_digitalocean.Volume.filesystem_label" title="Permalink to this definition">¶</a></dt>
<dd><p>Filesystem label for the block storage volume.</p>
</dd></dl>

<dl class="py attribute">
<dt id="pulumi_digitalocean.Volume.filesystem_type">
<code class="sig-name descname">filesystem_type</code><em class="property">: pulumi.Output[str]</em><em class="property"> = None</em><a class="headerlink" href="#pulumi_digitalocean.Volume.filesystem_type" title="Permalink to this definition">¶</a></dt>
<dd><p>Filesystem type (<code class="docutils literal notranslate"><span class="pre">xfs</span></code> or <code class="docutils literal notranslate"><span class="pre">ext4</span></code>) for the block storage volume.</p>
</dd></dl>

<dl class="py attribute">
<dt id="pulumi_digitalocean.Volume.initial_filesystem_label">
<code class="sig-name descname">initial_filesystem_label</code><em class="property">: pulumi.Output[str]</em><em class="property"> = None</em><a class="headerlink" href="#pulumi_digitalocean.Volume.initial_filesystem_label" title="Permalink to this definition">¶</a></dt>
<dd><p>Initial filesystem label for the block storage volume.</p>
</dd></dl>

<dl class="py attribute">
<dt id="pulumi_digitalocean.Volume.initial_filesystem_type">
<code class="sig-name descname">initial_filesystem_type</code><em class="property">: pulumi.Output[str]</em><em class="property"> = None</em><a class="headerlink" href="#pulumi_digitalocean.Volume.initial_filesystem_type" title="Permalink to this definition">¶</a></dt>
<dd><p>Initial filesystem type (<code class="docutils literal notranslate"><span class="pre">xfs</span></code> or <code class="docutils literal notranslate"><span class="pre">ext4</span></code>) for the block storage volume.</p>
</dd></dl>

<dl class="py attribute">
<dt id="pulumi_digitalocean.Volume.name">
<code class="sig-name descname">name</code><em class="property">: pulumi.Output[str]</em><em class="property"> = None</em><a class="headerlink" href="#pulumi_digitalocean.Volume.name" title="Permalink to this definition">¶</a></dt>
<dd><p>A name for the block storage volume. Must be lowercase and be composed only of numbers, letters and “-“, up to a limit of 64 characters.</p>
</dd></dl>

<dl class="py attribute">
<dt id="pulumi_digitalocean.Volume.region">
<code class="sig-name descname">region</code><em class="property">: pulumi.Output[str]</em><em class="property"> = None</em><a class="headerlink" href="#pulumi_digitalocean.Volume.region" title="Permalink to this definition">¶</a></dt>
<dd><p>The region that the block storage volume will be created in.</p>
</dd></dl>

<dl class="py attribute">
<dt id="pulumi_digitalocean.Volume.size">
<code class="sig-name descname">size</code><em class="property">: pulumi.Output[float]</em><em class="property"> = None</em><a class="headerlink" href="#pulumi_digitalocean.Volume.size" title="Permalink to this definition">¶</a></dt>
<dd><p>The size of the block storage volume in GiB. If updated, can only be expanded.</p>
</dd></dl>

<dl class="py attribute">
<dt id="pulumi_digitalocean.Volume.snapshot_id">
<code class="sig-name descname">snapshot_id</code><em class="property">: pulumi.Output[str]</em><em class="property"> = None</em><a class="headerlink" href="#pulumi_digitalocean.Volume.snapshot_id" title="Permalink to this definition">¶</a></dt>
<dd><p>The ID of an existing volume snapshot from which the new volume will be created. If supplied, the region and size will be limitied on creation to that of the referenced snapshot</p>
</dd></dl>

<dl class="py attribute">
<dt id="pulumi_digitalocean.Volume.tags">
<code class="sig-name descname">tags</code><em class="property">: pulumi.Output[list]</em><em class="property"> = None</em><a class="headerlink" href="#pulumi_digitalocean.Volume.tags" title="Permalink to this definition">¶</a></dt>
<dd><p>A list of the tags to be applied to this Volume.</p>
</dd></dl>

<dl class="py attribute">
<dt id="pulumi_digitalocean.Volume.urn">
<code class="sig-name descname">urn</code><em class="property">: pulumi.Output[str]</em><em class="property"> = None</em><a class="headerlink" href="#pulumi_digitalocean.Volume.urn" title="Permalink to this definition">¶</a></dt>
<dd><p>The uniform resource name for the volume.</p>
</dd></dl>

<dl class="py method">
<dt id="pulumi_digitalocean.Volume.get">
<em class="property">static </em><code class="sig-name descname">get</code><span class="sig-paren">(</span><em class="sig-param"><span class="n">resource_name</span></em>, <em class="sig-param"><span class="n">id</span></em>, <em class="sig-param"><span class="n">opts</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">description</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">droplet_ids</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">filesystem_label</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">filesystem_type</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">initial_filesystem_label</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">initial_filesystem_type</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">name</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">region</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">size</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">snapshot_id</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">tags</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">urn</span><span class="o">=</span><span class="default_value">None</span></em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_digitalocean.Volume.get" title="Permalink to this definition">¶</a></dt>
<dd><p>Get an existing Volume resource’s state with the given name, id, and optional extra
properties used to qualify the lookup.</p>
<dl class="field-list simple">
<dt class="field-odd">Parameters</dt>
<dd class="field-odd"><ul class="simple">
<li><p><strong>resource_name</strong> (<em>str</em>) – The unique name of the resulting resource.</p></li>
<li><p><strong>id</strong> (<em>str</em>) – The unique provider ID of the resource to lookup.</p></li>
<li><p><strong>opts</strong> (<a class="reference internal" href="../pulumi/#pulumi.ResourceOptions" title="pulumi.ResourceOptions"><em>pulumi.ResourceOptions</em></a>) – Options for the resource.</p></li>
<li><p><strong>description</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – A free-form text field up to a limit of 1024 bytes to describe a block storage volume.</p></li>
<li><p><strong>droplet_ids</strong> (<em>pulumi.Input</em><em>[</em><em>list</em><em>]</em>) – A list of associated droplet ids.</p></li>
<li><p><strong>filesystem_label</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – Filesystem label for the block storage volume.</p></li>
<li><p><strong>filesystem_type</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – Filesystem type (<code class="docutils literal notranslate"><span class="pre">xfs</span></code> or <code class="docutils literal notranslate"><span class="pre">ext4</span></code>) for the block storage volume.</p></li>
<li><p><strong>initial_filesystem_label</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – Initial filesystem label for the block storage volume.</p></li>
<li><p><strong>initial_filesystem_type</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – Initial filesystem type (<code class="docutils literal notranslate"><span class="pre">xfs</span></code> or <code class="docutils literal notranslate"><span class="pre">ext4</span></code>) for the block storage volume.</p></li>
<li><p><strong>name</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – A name for the block storage volume. Must be lowercase and be composed only of numbers, letters and “-“, up to a limit of 64 characters.</p></li>
<li><p><strong>region</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – The region that the block storage volume will be created in.</p></li>
<li><p><strong>size</strong> (<em>pulumi.Input</em><em>[</em><em>float</em><em>]</em>) – The size of the block storage volume in GiB. If updated, can only be expanded.</p></li>
<li><p><strong>snapshot_id</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – The ID of an existing volume snapshot from which the new volume will be created. If supplied, the region and size will be limitied on creation to that of the referenced snapshot</p></li>
<li><p><strong>tags</strong> (<em>pulumi.Input</em><em>[</em><em>list</em><em>]</em>) – A list of the tags to be applied to this Volume.</p></li>
<li><p><strong>urn</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – The uniform resource name for the volume.</p></li>
</ul>
</dd>
</dl>
</dd></dl>

<dl class="py method">
<dt id="pulumi_digitalocean.Volume.translate_output_property">
<code class="sig-name descname">translate_output_property</code><span class="sig-paren">(</span><em class="sig-param"><span class="n">prop</span></em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_digitalocean.Volume.translate_output_property" title="Permalink to this definition">¶</a></dt>
<dd><p>Provides subclasses of Resource an opportunity to translate names of output properties
into a format of their choosing before writing those properties to the resource object.</p>
<dl class="field-list simple">
<dt class="field-odd">Parameters</dt>
<dd class="field-odd"><p><strong>prop</strong> (<em>str</em>) – A property name.</p>
</dd>
<dt class="field-even">Returns</dt>
<dd class="field-even"><p>A potentially transformed property name.</p>
</dd>
<dt class="field-odd">Return type</dt>
<dd class="field-odd"><p>str</p>
</dd>
</dl>
</dd></dl>

<dl class="py method">
<dt id="pulumi_digitalocean.Volume.translate_input_property">
<code class="sig-name descname">translate_input_property</code><span class="sig-paren">(</span><em class="sig-param"><span class="n">prop</span></em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_digitalocean.Volume.translate_input_property" title="Permalink to this definition">¶</a></dt>
<dd><p>Provides subclasses of Resource an opportunity to translate names of input properties into
a format of their choosing before sending those properties to the Pulumi engine.</p>
<dl class="field-list simple">
<dt class="field-odd">Parameters</dt>
<dd class="field-odd"><p><strong>prop</strong> (<em>str</em>) – A property name.</p>
</dd>
<dt class="field-even">Returns</dt>
<dd class="field-even"><p>A potentially transformed property name.</p>
</dd>
<dt class="field-odd">Return type</dt>
<dd class="field-odd"><p>str</p>
</dd>
</dl>
</dd></dl>

</dd></dl>

<dl class="py class">
<dt id="pulumi_digitalocean.VolumeAttachment">
<em class="property">class </em><code class="sig-prename descclassname">pulumi_digitalocean.</code><code class="sig-name descname">VolumeAttachment</code><span class="sig-paren">(</span><em class="sig-param"><span class="n">resource_name</span></em>, <em class="sig-param"><span class="n">opts</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">droplet_id</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">volume_id</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">__props__</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">__name__</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">__opts__</span><span class="o">=</span><span class="default_value">None</span></em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_digitalocean.VolumeAttachment" title="Permalink to this definition">¶</a></dt>
<dd><p>Manages attaching a Volume to a Droplet.</p>
<blockquote>
<div><p><strong>NOTE:</strong> Volumes can be attached either directly on the <code class="docutils literal notranslate"><span class="pre">.Droplet</span></code> resource, or using the <code class="docutils literal notranslate"><span class="pre">.VolumeAttachment</span></code> resource - but the two cannot be used together. If both are used against the same Droplet, the volume attachments will constantly drift.</p>
</div></blockquote>
<div class="highlight-python notranslate"><div class="highlight"><pre><span></span><span class="kn">import</span> <span class="nn">pulumi</span>
<span class="kn">import</span> <span class="nn">pulumi_digitalocean</span> <span class="k">as</span> <span class="nn">digitalocean</span>

<span class="n">foobar_volume</span> <span class="o">=</span> <span class="n">digitalocean</span><span class="o">.</span><span class="n">Volume</span><span class="p">(</span><span class="s2">&quot;foobarVolume&quot;</span><span class="p">,</span>
    <span class="n">region</span><span class="o">=</span><span class="s2">&quot;nyc1&quot;</span><span class="p">,</span>
    <span class="n">size</span><span class="o">=</span><span class="mi">100</span><span class="p">,</span>
    <span class="n">initial_filesystem_type</span><span class="o">=</span><span class="s2">&quot;ext4&quot;</span><span class="p">,</span>
    <span class="n">description</span><span class="o">=</span><span class="s2">&quot;an example volume&quot;</span><span class="p">)</span>
<span class="n">foobar_droplet</span> <span class="o">=</span> <span class="n">digitalocean</span><span class="o">.</span><span class="n">Droplet</span><span class="p">(</span><span class="s2">&quot;foobarDroplet&quot;</span><span class="p">,</span>
    <span class="n">size</span><span class="o">=</span><span class="s2">&quot;s-1vcpu-1gb&quot;</span><span class="p">,</span>
    <span class="n">image</span><span class="o">=</span><span class="s2">&quot;ubuntu-18-04-x64&quot;</span><span class="p">,</span>
    <span class="n">region</span><span class="o">=</span><span class="s2">&quot;nyc1&quot;</span><span class="p">)</span>
<span class="n">foobar_volume_attachment</span> <span class="o">=</span> <span class="n">digitalocean</span><span class="o">.</span><span class="n">VolumeAttachment</span><span class="p">(</span><span class="s2">&quot;foobarVolumeAttachment&quot;</span><span class="p">,</span>
    <span class="n">droplet_id</span><span class="o">=</span><span class="n">foobar_droplet</span><span class="o">.</span><span class="n">id</span><span class="p">,</span>
    <span class="n">volume_id</span><span class="o">=</span><span class="n">foobar_volume</span><span class="o">.</span><span class="n">id</span><span class="p">)</span>
</pre></div>
</div>
<dl class="field-list simple">
<dt class="field-odd">Parameters</dt>
<dd class="field-odd"><ul class="simple">
<li><p><strong>resource_name</strong> (<em>str</em>) – The name of the resource.</p></li>
<li><p><strong>opts</strong> (<a class="reference internal" href="../pulumi/#pulumi.ResourceOptions" title="pulumi.ResourceOptions"><em>pulumi.ResourceOptions</em></a>) – Options for the resource.</p></li>
<li><p><strong>droplet_id</strong> (<em>pulumi.Input</em><em>[</em><em>float</em><em>]</em>) – ID of the Droplet to attach the volume to.</p></li>
<li><p><strong>volume_id</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – ID of the Volume to be attached to the Droplet.</p></li>
</ul>
</dd>
</dl>
<dl class="py attribute">
<dt id="pulumi_digitalocean.VolumeAttachment.droplet_id">
<code class="sig-name descname">droplet_id</code><em class="property">: pulumi.Output[float]</em><em class="property"> = None</em><a class="headerlink" href="#pulumi_digitalocean.VolumeAttachment.droplet_id" title="Permalink to this definition">¶</a></dt>
<dd><p>ID of the Droplet to attach the volume to.</p>
</dd></dl>

<dl class="py attribute">
<dt id="pulumi_digitalocean.VolumeAttachment.volume_id">
<code class="sig-name descname">volume_id</code><em class="property">: pulumi.Output[str]</em><em class="property"> = None</em><a class="headerlink" href="#pulumi_digitalocean.VolumeAttachment.volume_id" title="Permalink to this definition">¶</a></dt>
<dd><p>ID of the Volume to be attached to the Droplet.</p>
</dd></dl>

<dl class="py method">
<dt id="pulumi_digitalocean.VolumeAttachment.get">
<em class="property">static </em><code class="sig-name descname">get</code><span class="sig-paren">(</span><em class="sig-param"><span class="n">resource_name</span></em>, <em class="sig-param"><span class="n">id</span></em>, <em class="sig-param"><span class="n">opts</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">droplet_id</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">volume_id</span><span class="o">=</span><span class="default_value">None</span></em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_digitalocean.VolumeAttachment.get" title="Permalink to this definition">¶</a></dt>
<dd><p>Get an existing VolumeAttachment resource’s state with the given name, id, and optional extra
properties used to qualify the lookup.</p>
<dl class="field-list simple">
<dt class="field-odd">Parameters</dt>
<dd class="field-odd"><ul class="simple">
<li><p><strong>resource_name</strong> (<em>str</em>) – The unique name of the resulting resource.</p></li>
<li><p><strong>id</strong> (<em>str</em>) – The unique provider ID of the resource to lookup.</p></li>
<li><p><strong>opts</strong> (<a class="reference internal" href="../pulumi/#pulumi.ResourceOptions" title="pulumi.ResourceOptions"><em>pulumi.ResourceOptions</em></a>) – Options for the resource.</p></li>
<li><p><strong>droplet_id</strong> (<em>pulumi.Input</em><em>[</em><em>float</em><em>]</em>) – ID of the Droplet to attach the volume to.</p></li>
<li><p><strong>volume_id</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – ID of the Volume to be attached to the Droplet.</p></li>
</ul>
</dd>
</dl>
</dd></dl>

<dl class="py method">
<dt id="pulumi_digitalocean.VolumeAttachment.translate_output_property">
<code class="sig-name descname">translate_output_property</code><span class="sig-paren">(</span><em class="sig-param"><span class="n">prop</span></em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_digitalocean.VolumeAttachment.translate_output_property" title="Permalink to this definition">¶</a></dt>
<dd><p>Provides subclasses of Resource an opportunity to translate names of output properties
into a format of their choosing before writing those properties to the resource object.</p>
<dl class="field-list simple">
<dt class="field-odd">Parameters</dt>
<dd class="field-odd"><p><strong>prop</strong> (<em>str</em>) – A property name.</p>
</dd>
<dt class="field-even">Returns</dt>
<dd class="field-even"><p>A potentially transformed property name.</p>
</dd>
<dt class="field-odd">Return type</dt>
<dd class="field-odd"><p>str</p>
</dd>
</dl>
</dd></dl>

<dl class="py method">
<dt id="pulumi_digitalocean.VolumeAttachment.translate_input_property">
<code class="sig-name descname">translate_input_property</code><span class="sig-paren">(</span><em class="sig-param"><span class="n">prop</span></em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_digitalocean.VolumeAttachment.translate_input_property" title="Permalink to this definition">¶</a></dt>
<dd><p>Provides subclasses of Resource an opportunity to translate names of input properties into
a format of their choosing before sending those properties to the Pulumi engine.</p>
<dl class="field-list simple">
<dt class="field-odd">Parameters</dt>
<dd class="field-odd"><p><strong>prop</strong> (<em>str</em>) – A property name.</p>
</dd>
<dt class="field-even">Returns</dt>
<dd class="field-even"><p>A potentially transformed property name.</p>
</dd>
<dt class="field-odd">Return type</dt>
<dd class="field-odd"><p>str</p>
</dd>
</dl>
</dd></dl>

</dd></dl>

<dl class="py class">
<dt id="pulumi_digitalocean.VolumeSnapshot">
<em class="property">class </em><code class="sig-prename descclassname">pulumi_digitalocean.</code><code class="sig-name descname">VolumeSnapshot</code><span class="sig-paren">(</span><em class="sig-param"><span class="n">resource_name</span></em>, <em class="sig-param"><span class="n">opts</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">name</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">tags</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">volume_id</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">__props__</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">__name__</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">__opts__</span><span class="o">=</span><span class="default_value">None</span></em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_digitalocean.VolumeSnapshot" title="Permalink to this definition">¶</a></dt>
<dd><p>Provides a DigitalOcean Volume Snapshot which can be used to create a snapshot from an existing volume.</p>
<div class="highlight-python notranslate"><div class="highlight"><pre><span></span><span class="kn">import</span> <span class="nn">pulumi</span>
<span class="kn">import</span> <span class="nn">pulumi_digitalocean</span> <span class="k">as</span> <span class="nn">digitalocean</span>

<span class="n">foobar_volume</span> <span class="o">=</span> <span class="n">digitalocean</span><span class="o">.</span><span class="n">Volume</span><span class="p">(</span><span class="s2">&quot;foobarVolume&quot;</span><span class="p">,</span>
    <span class="n">region</span><span class="o">=</span><span class="s2">&quot;nyc1&quot;</span><span class="p">,</span>
    <span class="n">size</span><span class="o">=</span><span class="mi">100</span><span class="p">,</span>
    <span class="n">description</span><span class="o">=</span><span class="s2">&quot;an example volume&quot;</span><span class="p">)</span>
<span class="n">foobar_volume_snapshot</span> <span class="o">=</span> <span class="n">digitalocean</span><span class="o">.</span><span class="n">VolumeSnapshot</span><span class="p">(</span><span class="s2">&quot;foobarVolumeSnapshot&quot;</span><span class="p">,</span> <span class="n">volume_id</span><span class="o">=</span><span class="n">foobar_volume</span><span class="o">.</span><span class="n">id</span><span class="p">)</span>
</pre></div>
</div>
<dl class="field-list simple">
<dt class="field-odd">Parameters</dt>
<dd class="field-odd"><ul class="simple">
<li><p><strong>resource_name</strong> (<em>str</em>) – The name of the resource.</p></li>
<li><p><strong>opts</strong> (<a class="reference internal" href="../pulumi/#pulumi.ResourceOptions" title="pulumi.ResourceOptions"><em>pulumi.ResourceOptions</em></a>) – Options for the resource.</p></li>
<li><p><strong>name</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – A name for the volume snapshot.</p></li>
<li><p><strong>tags</strong> (<em>pulumi.Input</em><em>[</em><em>list</em><em>]</em>) – A list of the tags to be applied to this volume snapshot.</p></li>
<li><p><strong>volume_id</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – The ID of the volume from which the volume snapshot originated.</p></li>
</ul>
</dd>
</dl>
<dl class="py attribute">
<dt id="pulumi_digitalocean.VolumeSnapshot.created_at">
<code class="sig-name descname">created_at</code><em class="property">: pulumi.Output[str]</em><em class="property"> = None</em><a class="headerlink" href="#pulumi_digitalocean.VolumeSnapshot.created_at" title="Permalink to this definition">¶</a></dt>
<dd><p>The date and time the volume snapshot was created.</p>
</dd></dl>

<dl class="py attribute">
<dt id="pulumi_digitalocean.VolumeSnapshot.min_disk_size">
<code class="sig-name descname">min_disk_size</code><em class="property">: pulumi.Output[float]</em><em class="property"> = None</em><a class="headerlink" href="#pulumi_digitalocean.VolumeSnapshot.min_disk_size" title="Permalink to this definition">¶</a></dt>
<dd><p>The minimum size in gigabytes required for a volume to be created based on this volume snapshot.</p>
</dd></dl>

<dl class="py attribute">
<dt id="pulumi_digitalocean.VolumeSnapshot.name">
<code class="sig-name descname">name</code><em class="property">: pulumi.Output[str]</em><em class="property"> = None</em><a class="headerlink" href="#pulumi_digitalocean.VolumeSnapshot.name" title="Permalink to this definition">¶</a></dt>
<dd><p>A name for the volume snapshot.</p>
</dd></dl>

<dl class="py attribute">
<dt id="pulumi_digitalocean.VolumeSnapshot.regions">
<code class="sig-name descname">regions</code><em class="property">: pulumi.Output[list]</em><em class="property"> = None</em><a class="headerlink" href="#pulumi_digitalocean.VolumeSnapshot.regions" title="Permalink to this definition">¶</a></dt>
<dd><p>A list of DigitalOcean region “slugs” indicating where the volume snapshot is available.</p>
</dd></dl>

<dl class="py attribute">
<dt id="pulumi_digitalocean.VolumeSnapshot.size">
<code class="sig-name descname">size</code><em class="property">: pulumi.Output[float]</em><em class="property"> = None</em><a class="headerlink" href="#pulumi_digitalocean.VolumeSnapshot.size" title="Permalink to this definition">¶</a></dt>
<dd><p>The billable size of the volume snapshot in gigabytes.</p>
</dd></dl>

<dl class="py attribute">
<dt id="pulumi_digitalocean.VolumeSnapshot.tags">
<code class="sig-name descname">tags</code><em class="property">: pulumi.Output[list]</em><em class="property"> = None</em><a class="headerlink" href="#pulumi_digitalocean.VolumeSnapshot.tags" title="Permalink to this definition">¶</a></dt>
<dd><p>A list of the tags to be applied to this volume snapshot.</p>
</dd></dl>

<dl class="py attribute">
<dt id="pulumi_digitalocean.VolumeSnapshot.volume_id">
<code class="sig-name descname">volume_id</code><em class="property">: pulumi.Output[str]</em><em class="property"> = None</em><a class="headerlink" href="#pulumi_digitalocean.VolumeSnapshot.volume_id" title="Permalink to this definition">¶</a></dt>
<dd><p>The ID of the volume from which the volume snapshot originated.</p>
</dd></dl>

<dl class="py method">
<dt id="pulumi_digitalocean.VolumeSnapshot.get">
<em class="property">static </em><code class="sig-name descname">get</code><span class="sig-paren">(</span><em class="sig-param"><span class="n">resource_name</span></em>, <em class="sig-param"><span class="n">id</span></em>, <em class="sig-param"><span class="n">opts</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">created_at</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">min_disk_size</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">name</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">regions</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">size</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">tags</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">volume_id</span><span class="o">=</span><span class="default_value">None</span></em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_digitalocean.VolumeSnapshot.get" title="Permalink to this definition">¶</a></dt>
<dd><p>Get an existing VolumeSnapshot resource’s state with the given name, id, and optional extra
properties used to qualify the lookup.</p>
<dl class="field-list simple">
<dt class="field-odd">Parameters</dt>
<dd class="field-odd"><ul class="simple">
<li><p><strong>resource_name</strong> (<em>str</em>) – The unique name of the resulting resource.</p></li>
<li><p><strong>id</strong> (<em>str</em>) – The unique provider ID of the resource to lookup.</p></li>
<li><p><strong>opts</strong> (<a class="reference internal" href="../pulumi/#pulumi.ResourceOptions" title="pulumi.ResourceOptions"><em>pulumi.ResourceOptions</em></a>) – Options for the resource.</p></li>
<li><p><strong>created_at</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – The date and time the volume snapshot was created.</p></li>
<li><p><strong>min_disk_size</strong> (<em>pulumi.Input</em><em>[</em><em>float</em><em>]</em>) – The minimum size in gigabytes required for a volume to be created based on this volume snapshot.</p></li>
<li><p><strong>name</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – A name for the volume snapshot.</p></li>
<li><p><strong>regions</strong> (<em>pulumi.Input</em><em>[</em><em>list</em><em>]</em>) – A list of DigitalOcean region “slugs” indicating where the volume snapshot is available.</p></li>
<li><p><strong>size</strong> (<em>pulumi.Input</em><em>[</em><em>float</em><em>]</em>) – The billable size of the volume snapshot in gigabytes.</p></li>
<li><p><strong>tags</strong> (<em>pulumi.Input</em><em>[</em><em>list</em><em>]</em>) – A list of the tags to be applied to this volume snapshot.</p></li>
<li><p><strong>volume_id</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – The ID of the volume from which the volume snapshot originated.</p></li>
</ul>
</dd>
</dl>
</dd></dl>

<dl class="py method">
<dt id="pulumi_digitalocean.VolumeSnapshot.translate_output_property">
<code class="sig-name descname">translate_output_property</code><span class="sig-paren">(</span><em class="sig-param"><span class="n">prop</span></em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_digitalocean.VolumeSnapshot.translate_output_property" title="Permalink to this definition">¶</a></dt>
<dd><p>Provides subclasses of Resource an opportunity to translate names of output properties
into a format of their choosing before writing those properties to the resource object.</p>
<dl class="field-list simple">
<dt class="field-odd">Parameters</dt>
<dd class="field-odd"><p><strong>prop</strong> (<em>str</em>) – A property name.</p>
</dd>
<dt class="field-even">Returns</dt>
<dd class="field-even"><p>A potentially transformed property name.</p>
</dd>
<dt class="field-odd">Return type</dt>
<dd class="field-odd"><p>str</p>
</dd>
</dl>
</dd></dl>

<dl class="py method">
<dt id="pulumi_digitalocean.VolumeSnapshot.translate_input_property">
<code class="sig-name descname">translate_input_property</code><span class="sig-paren">(</span><em class="sig-param"><span class="n">prop</span></em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_digitalocean.VolumeSnapshot.translate_input_property" title="Permalink to this definition">¶</a></dt>
<dd><p>Provides subclasses of Resource an opportunity to translate names of input properties into
a format of their choosing before sending those properties to the Pulumi engine.</p>
<dl class="field-list simple">
<dt class="field-odd">Parameters</dt>
<dd class="field-odd"><p><strong>prop</strong> (<em>str</em>) – A property name.</p>
</dd>
<dt class="field-even">Returns</dt>
<dd class="field-even"><p>A potentially transformed property name.</p>
</dd>
<dt class="field-odd">Return type</dt>
<dd class="field-odd"><p>str</p>
</dd>
</dl>
</dd></dl>

</dd></dl>

<dl class="py class">
<dt id="pulumi_digitalocean.Vpc">
<em class="property">class </em><code class="sig-prename descclassname">pulumi_digitalocean.</code><code class="sig-name descname">Vpc</code><span class="sig-paren">(</span><em class="sig-param"><span class="n">resource_name</span></em>, <em class="sig-param"><span class="n">opts</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">description</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">ip_range</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">name</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">region</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">__props__</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">__name__</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">__opts__</span><span class="o">=</span><span class="default_value">None</span></em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_digitalocean.Vpc" title="Permalink to this definition">¶</a></dt>
<dd><p>Provides a <a class="reference external" href="https://developers.digitalocean.com/documentation/v2/#vpcs">DigitalOcean VPC</a> resource.</p>
<p>VPCs are virtual networks containing resources that can communicate with each
other in full isolation, using private IP addresses.</p>
<div class="highlight-python notranslate"><div class="highlight"><pre><span></span><span class="kn">import</span> <span class="nn">pulumi</span>
<span class="kn">import</span> <span class="nn">pulumi_digitalocean</span> <span class="k">as</span> <span class="nn">digitalocean</span>

<span class="n">example</span> <span class="o">=</span> <span class="n">digitalocean</span><span class="o">.</span><span class="n">Vpc</span><span class="p">(</span><span class="s2">&quot;example&quot;</span><span class="p">,</span>
    <span class="n">ip_range</span><span class="o">=</span><span class="s2">&quot;10.10.10.0/24&quot;</span><span class="p">,</span>
    <span class="n">region</span><span class="o">=</span><span class="s2">&quot;nyc3&quot;</span><span class="p">)</span>
</pre></div>
</div>
<div class="highlight-python notranslate"><div class="highlight"><pre><span></span><span class="kn">import</span> <span class="nn">pulumi</span>
<span class="kn">import</span> <span class="nn">pulumi_digitalocean</span> <span class="k">as</span> <span class="nn">digitalocean</span>

<span class="n">example_vpc</span> <span class="o">=</span> <span class="n">digitalocean</span><span class="o">.</span><span class="n">Vpc</span><span class="p">(</span><span class="s2">&quot;exampleVpc&quot;</span><span class="p">,</span> <span class="n">region</span><span class="o">=</span><span class="s2">&quot;nyc3&quot;</span><span class="p">)</span>
<span class="n">example_droplet</span> <span class="o">=</span> <span class="n">digitalocean</span><span class="o">.</span><span class="n">Droplet</span><span class="p">(</span><span class="s2">&quot;exampleDroplet&quot;</span><span class="p">,</span>
    <span class="n">size</span><span class="o">=</span><span class="s2">&quot;s-1vcpu-1gb&quot;</span><span class="p">,</span>
    <span class="n">image</span><span class="o">=</span><span class="s2">&quot;ubuntu-18-04-x64&quot;</span><span class="p">,</span>
    <span class="n">region</span><span class="o">=</span><span class="s2">&quot;nyc3&quot;</span><span class="p">,</span>
    <span class="n">vpc_uuid</span><span class="o">=</span><span class="n">example_vpc</span><span class="o">.</span><span class="n">id</span><span class="p">)</span>
</pre></div>
</div>
<dl class="field-list simple">
<dt class="field-odd">Parameters</dt>
<dd class="field-odd"><ul class="simple">
<li><p><strong>resource_name</strong> (<em>str</em>) – The name of the resource.</p></li>
<li><p><strong>opts</strong> (<a class="reference internal" href="../pulumi/#pulumi.ResourceOptions" title="pulumi.ResourceOptions"><em>pulumi.ResourceOptions</em></a>) – Options for the resource.</p></li>
<li><p><strong>description</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – A free-form text field up to a limit of 255 characters to describe the VPC.</p></li>
<li><p><strong>ip_range</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – The range of IP addresses for the VPC in CIDR notation. Network ranges cannot overlap with other networks in the same account and must be in range of private addresses as defined in RFC1918. It may not be larger than <code class="docutils literal notranslate"><span class="pre">/16</span></code> or smaller than <code class="docutils literal notranslate"><span class="pre">/24</span></code>.</p></li>
<li><p><strong>name</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – A name for the VPC. Must be unique and contain alphanumeric characters, dashes, and periods only.</p></li>
<li><p><strong>region</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – The DigitalOcean region slug for the VPC’s location.</p></li>
</ul>
</dd>
</dl>
<dl class="py attribute">
<dt id="pulumi_digitalocean.Vpc.created_at">
<code class="sig-name descname">created_at</code><em class="property">: pulumi.Output[str]</em><em class="property"> = None</em><a class="headerlink" href="#pulumi_digitalocean.Vpc.created_at" title="Permalink to this definition">¶</a></dt>
<dd><p>The date and time of when the VPC was created.</p>
</dd></dl>

<dl class="py attribute">
<dt id="pulumi_digitalocean.Vpc.default">
<code class="sig-name descname">default</code><em class="property">: pulumi.Output[bool]</em><em class="property"> = None</em><a class="headerlink" href="#pulumi_digitalocean.Vpc.default" title="Permalink to this definition">¶</a></dt>
<dd><p>A boolean indicating whether or not the VPC is the default one for the region.</p>
</dd></dl>

<dl class="py attribute">
<dt id="pulumi_digitalocean.Vpc.description">
<code class="sig-name descname">description</code><em class="property">: pulumi.Output[str]</em><em class="property"> = None</em><a class="headerlink" href="#pulumi_digitalocean.Vpc.description" title="Permalink to this definition">¶</a></dt>
<dd><p>A free-form text field up to a limit of 255 characters to describe the VPC.</p>
</dd></dl>

<dl class="py attribute">
<dt id="pulumi_digitalocean.Vpc.ip_range">
<code class="sig-name descname">ip_range</code><em class="property">: pulumi.Output[str]</em><em class="property"> = None</em><a class="headerlink" href="#pulumi_digitalocean.Vpc.ip_range" title="Permalink to this definition">¶</a></dt>
<dd><p>The range of IP addresses for the VPC in CIDR notation. Network ranges cannot overlap with other networks in the same account and must be in range of private addresses as defined in RFC1918. It may not be larger than <code class="docutils literal notranslate"><span class="pre">/16</span></code> or smaller than <code class="docutils literal notranslate"><span class="pre">/24</span></code>.</p>
</dd></dl>

<dl class="py attribute">
<dt id="pulumi_digitalocean.Vpc.name">
<code class="sig-name descname">name</code><em class="property">: pulumi.Output[str]</em><em class="property"> = None</em><a class="headerlink" href="#pulumi_digitalocean.Vpc.name" title="Permalink to this definition">¶</a></dt>
<dd><p>A name for the VPC. Must be unique and contain alphanumeric characters, dashes, and periods only.</p>
</dd></dl>

<dl class="py attribute">
<dt id="pulumi_digitalocean.Vpc.region">
<code class="sig-name descname">region</code><em class="property">: pulumi.Output[str]</em><em class="property"> = None</em><a class="headerlink" href="#pulumi_digitalocean.Vpc.region" title="Permalink to this definition">¶</a></dt>
<dd><p>The DigitalOcean region slug for the VPC’s location.</p>
</dd></dl>

<dl class="py attribute">
<dt id="pulumi_digitalocean.Vpc.urn">
<code class="sig-name descname">urn</code><em class="property">: pulumi.Output[str]</em><em class="property"> = None</em><a class="headerlink" href="#pulumi_digitalocean.Vpc.urn" title="Permalink to this definition">¶</a></dt>
<dd><p>The uniform resource name (URN) for the VPC.</p>
</dd></dl>

<dl class="py method">
<dt id="pulumi_digitalocean.Vpc.get">
<em class="property">static </em><code class="sig-name descname">get</code><span class="sig-paren">(</span><em class="sig-param"><span class="n">resource_name</span></em>, <em class="sig-param"><span class="n">id</span></em>, <em class="sig-param"><span class="n">opts</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">created_at</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">default</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">description</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">ip_range</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">name</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">region</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">urn</span><span class="o">=</span><span class="default_value">None</span></em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_digitalocean.Vpc.get" title="Permalink to this definition">¶</a></dt>
<dd><p>Get an existing Vpc resource’s state with the given name, id, and optional extra
properties used to qualify the lookup.</p>
<dl class="field-list simple">
<dt class="field-odd">Parameters</dt>
<dd class="field-odd"><ul class="simple">
<li><p><strong>resource_name</strong> (<em>str</em>) – The unique name of the resulting resource.</p></li>
<li><p><strong>id</strong> (<em>str</em>) – The unique provider ID of the resource to lookup.</p></li>
<li><p><strong>opts</strong> (<a class="reference internal" href="../pulumi/#pulumi.ResourceOptions" title="pulumi.ResourceOptions"><em>pulumi.ResourceOptions</em></a>) – Options for the resource.</p></li>
<li><p><strong>created_at</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – The date and time of when the VPC was created.</p></li>
<li><p><strong>default</strong> (<em>pulumi.Input</em><em>[</em><em>bool</em><em>]</em>) – A boolean indicating whether or not the VPC is the default one for the region.</p></li>
<li><p><strong>description</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – A free-form text field up to a limit of 255 characters to describe the VPC.</p></li>
<li><p><strong>ip_range</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – The range of IP addresses for the VPC in CIDR notation. Network ranges cannot overlap with other networks in the same account and must be in range of private addresses as defined in RFC1918. It may not be larger than <code class="docutils literal notranslate"><span class="pre">/16</span></code> or smaller than <code class="docutils literal notranslate"><span class="pre">/24</span></code>.</p></li>
<li><p><strong>name</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – A name for the VPC. Must be unique and contain alphanumeric characters, dashes, and periods only.</p></li>
<li><p><strong>region</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – The DigitalOcean region slug for the VPC’s location.</p></li>
<li><p><strong>urn</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – The uniform resource name (URN) for the VPC.</p></li>
</ul>
</dd>
</dl>
</dd></dl>

<dl class="py method">
<dt id="pulumi_digitalocean.Vpc.translate_output_property">
<code class="sig-name descname">translate_output_property</code><span class="sig-paren">(</span><em class="sig-param"><span class="n">prop</span></em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_digitalocean.Vpc.translate_output_property" title="Permalink to this definition">¶</a></dt>
<dd><p>Provides subclasses of Resource an opportunity to translate names of output properties
into a format of their choosing before writing those properties to the resource object.</p>
<dl class="field-list simple">
<dt class="field-odd">Parameters</dt>
<dd class="field-odd"><p><strong>prop</strong> (<em>str</em>) – A property name.</p>
</dd>
<dt class="field-even">Returns</dt>
<dd class="field-even"><p>A potentially transformed property name.</p>
</dd>
<dt class="field-odd">Return type</dt>
<dd class="field-odd"><p>str</p>
</dd>
</dl>
</dd></dl>

<dl class="py method">
<dt id="pulumi_digitalocean.Vpc.translate_input_property">
<code class="sig-name descname">translate_input_property</code><span class="sig-paren">(</span><em class="sig-param"><span class="n">prop</span></em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_digitalocean.Vpc.translate_input_property" title="Permalink to this definition">¶</a></dt>
<dd><p>Provides subclasses of Resource an opportunity to translate names of input properties into
a format of their choosing before sending those properties to the Pulumi engine.</p>
<dl class="field-list simple">
<dt class="field-odd">Parameters</dt>
<dd class="field-odd"><p><strong>prop</strong> (<em>str</em>) – A property name.</p>
</dd>
<dt class="field-even">Returns</dt>
<dd class="field-even"><p>A potentially transformed property name.</p>
</dd>
<dt class="field-odd">Return type</dt>
<dd class="field-odd"><p>str</p>
</dd>
</dl>
</dd></dl>

</dd></dl>

<dl class="py function">
<dt id="pulumi_digitalocean.get_account">
<code class="sig-prename descclassname">pulumi_digitalocean.</code><code class="sig-name descname">get_account</code><span class="sig-paren">(</span><em class="sig-param"><span class="n">opts</span><span class="o">=</span><span class="default_value">None</span></em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_digitalocean.get_account" title="Permalink to this definition">¶</a></dt>
<dd><p>Get information on your DigitalOcean account.</p>
<div class="highlight-python notranslate"><div class="highlight"><pre><span></span><span class="kn">import</span> <span class="nn">pulumi</span>
<span class="kn">import</span> <span class="nn">pulumi_digitalocean</span> <span class="k">as</span> <span class="nn">digitalocean</span>

<span class="n">example</span> <span class="o">=</span> <span class="n">digitalocean</span><span class="o">.</span><span class="n">get_account</span><span class="p">()</span>
</pre></div>
</div>
</dd></dl>

<dl class="py function">
<dt id="pulumi_digitalocean.get_certificate">
<code class="sig-prename descclassname">pulumi_digitalocean.</code><code class="sig-name descname">get_certificate</code><span class="sig-paren">(</span><em class="sig-param"><span class="n">name</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">opts</span><span class="o">=</span><span class="default_value">None</span></em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_digitalocean.get_certificate" title="Permalink to this definition">¶</a></dt>
<dd><p>Use this data source to access information about an existing resource.</p>
<dl class="field-list simple">
<dt class="field-odd">Parameters</dt>
<dd class="field-odd"><p><strong>name</strong> (<em>str</em>) – The name of certificate.</p>
</dd>
</dl>
</dd></dl>

<dl class="py function">
<dt id="pulumi_digitalocean.get_database_cluster">
<code class="sig-prename descclassname">pulumi_digitalocean.</code><code class="sig-name descname">get_database_cluster</code><span class="sig-paren">(</span><em class="sig-param"><span class="n">name</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">tags</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">opts</span><span class="o">=</span><span class="default_value">None</span></em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_digitalocean.get_database_cluster" title="Permalink to this definition">¶</a></dt>
<dd><p>Provides information on a DigitalOcean database cluster resource.</p>
<div class="highlight-python notranslate"><div class="highlight"><pre><span></span><span class="kn">import</span> <span class="nn">pulumi</span>
<span class="kn">import</span> <span class="nn">pulumi_digitalocean</span> <span class="k">as</span> <span class="nn">digitalocean</span>

<span class="n">example</span> <span class="o">=</span> <span class="n">digitalocean</span><span class="o">.</span><span class="n">get_database_cluster</span><span class="p">(</span><span class="n">name</span><span class="o">=</span><span class="s2">&quot;example-cluster&quot;</span><span class="p">)</span>
<span class="n">pulumi</span><span class="o">.</span><span class="n">export</span><span class="p">(</span><span class="s2">&quot;databaseOutput&quot;</span><span class="p">,</span> <span class="n">example</span><span class="o">.</span><span class="n">uri</span><span class="p">)</span>
</pre></div>
</div>
<dl class="field-list simple">
<dt class="field-odd">Parameters</dt>
<dd class="field-odd"><p><strong>name</strong> (<em>str</em>) – The name of the database cluster.</p>
</dd>
</dl>
</dd></dl>

<dl class="py function">
<dt id="pulumi_digitalocean.get_domain">
<code class="sig-prename descclassname">pulumi_digitalocean.</code><code class="sig-name descname">get_domain</code><span class="sig-paren">(</span><em class="sig-param"><span class="n">name</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">opts</span><span class="o">=</span><span class="default_value">None</span></em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_digitalocean.get_domain" title="Permalink to this definition">¶</a></dt>
<dd><p>Use this data source to access information about an existing resource.</p>
<dl class="field-list simple">
<dt class="field-odd">Parameters</dt>
<dd class="field-odd"><p><strong>name</strong> (<em>str</em>) – The name of the domain.</p>
</dd>
</dl>
</dd></dl>

<dl class="py function">
<dt id="pulumi_digitalocean.get_droplet">
<code class="sig-prename descclassname">pulumi_digitalocean.</code><code class="sig-name descname">get_droplet</code><span class="sig-paren">(</span><em class="sig-param"><span class="n">id</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">name</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">tag</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">opts</span><span class="o">=</span><span class="default_value">None</span></em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_digitalocean.get_droplet" title="Permalink to this definition">¶</a></dt>
<dd><p>Use this data source to access information about an existing resource.</p>
<dl class="field-list simple">
<dt class="field-odd">Parameters</dt>
<dd class="field-odd"><ul class="simple">
<li><p><strong>id</strong> (<em>float</em>) – The ID of the Droplet</p></li>
<li><p><strong>name</strong> (<em>str</em>) – The name of the Droplet.</p></li>
<li><p><strong>tag</strong> (<em>str</em>) – A tag applied to the Droplet.</p></li>
</ul>
</dd>
</dl>
</dd></dl>

<dl class="py function">
<dt id="pulumi_digitalocean.get_droplet_snapshot">
<code class="sig-prename descclassname">pulumi_digitalocean.</code><code class="sig-name descname">get_droplet_snapshot</code><span class="sig-paren">(</span><em class="sig-param"><span class="n">most_recent</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">name</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">name_regex</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">region</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">opts</span><span class="o">=</span><span class="default_value">None</span></em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_digitalocean.get_droplet_snapshot" title="Permalink to this definition">¶</a></dt>
<dd><p>Droplet snapshots are saved instances of a Droplet. Use this data
source to retrieve the ID of a DigitalOcean Droplet snapshot for use in other
resources.</p>
<div class="highlight-python notranslate"><div class="highlight"><pre><span></span><span class="kn">import</span> <span class="nn">pulumi</span>
<span class="kn">import</span> <span class="nn">pulumi_digitalocean</span> <span class="k">as</span> <span class="nn">digitalocean</span>

<span class="n">web_snapshot</span> <span class="o">=</span> <span class="n">digitalocean</span><span class="o">.</span><span class="n">get_droplet_snapshot</span><span class="p">(</span><span class="n">most_recent</span><span class="o">=</span><span class="kc">True</span><span class="p">,</span>
    <span class="n">name_regex</span><span class="o">=</span><span class="s2">&quot;^web&quot;</span><span class="p">,</span>
    <span class="n">region</span><span class="o">=</span><span class="s2">&quot;nyc3&quot;</span><span class="p">)</span>
</pre></div>
</div>
<dl class="field-list simple">
<dt class="field-odd">Parameters</dt>
<dd class="field-odd"><ul class="simple">
<li><p><strong>most_recent</strong> (<em>bool</em>) – If more than one result is returned, use the most recent Droplet snapshot.</p></li>
<li><p><strong>name</strong> (<em>str</em>) – The name of the Droplet snapshot.</p></li>
<li><p><strong>name_regex</strong> (<em>str</em>) – A regex string to apply to the Droplet snapshot list returned by DigitalOcean. This allows more advanced filtering not supported from the DigitalOcean API. This filtering is done locally on what DigitalOcean returns.</p></li>
<li><p><strong>region</strong> (<em>str</em>) – A “slug” representing a DigitalOcean region (e.g. <code class="docutils literal notranslate"><span class="pre">nyc1</span></code>). If set, only Droplet snapshots available in the region will be returned.</p></li>
</ul>
</dd>
</dl>
</dd></dl>

<dl class="py function">
<dt id="pulumi_digitalocean.get_droplets">
<code class="sig-prename descclassname">pulumi_digitalocean.</code><code class="sig-name descname">get_droplets</code><span class="sig-paren">(</span><em class="sig-param"><span class="n">filters</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">sorts</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">opts</span><span class="o">=</span><span class="default_value">None</span></em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_digitalocean.get_droplets" title="Permalink to this definition">¶</a></dt>
<dd><p>Use this data source to access information about an existing resource.</p>
<dl class="field-list simple">
<dt class="field-odd">Parameters</dt>
<dd class="field-odd"><ul class="simple">
<li><p><strong>filters</strong> (<em>list</em>) – Filter the results.
The <code class="docutils literal notranslate"><span class="pre">filter</span></code> block is documented below.</p></li>
<li><p><strong>sorts</strong> (<em>list</em>) – Sort the results.
The <code class="docutils literal notranslate"><span class="pre">sort</span></code> block is documented below.</p></li>
</ul>
</dd>
</dl>
<p>The <strong>filters</strong> object supports the following:</p>
<ul class="simple">
<li><p><code class="docutils literal notranslate"><span class="pre">key</span></code> (<code class="docutils literal notranslate"><span class="pre">str</span></code>) - Filter the Droplets by this key. This may be one of ‘<code class="docutils literal notranslate"><span class="pre">backups</span></code>, <code class="docutils literal notranslate"><span class="pre">created_at</span></code>, <code class="docutils literal notranslate"><span class="pre">disk</span></code>, <code class="docutils literal notranslate"><span class="pre">id</span></code>,
<code class="docutils literal notranslate"><span class="pre">image</span></code>, <code class="docutils literal notranslate"><span class="pre">ipv4_address</span></code>, <code class="docutils literal notranslate"><span class="pre">ipv4_address_private</span></code>, <code class="docutils literal notranslate"><span class="pre">ipv6</span></code>, <code class="docutils literal notranslate"><span class="pre">ipv6_address</span></code>, <code class="docutils literal notranslate"><span class="pre">ipv6_address_private</span></code>, <code class="docutils literal notranslate"><span class="pre">locked</span></code>,
<code class="docutils literal notranslate"><span class="pre">memory</span></code>, <code class="docutils literal notranslate"><span class="pre">monitoring</span></code>, <code class="docutils literal notranslate"><span class="pre">name</span></code>, <code class="docutils literal notranslate"><span class="pre">price_hourly</span></code>, <code class="docutils literal notranslate"><span class="pre">price_monthly</span></code>, <code class="docutils literal notranslate"><span class="pre">private_networking</span></code>, <code class="docutils literal notranslate"><span class="pre">region</span></code>, <code class="docutils literal notranslate"><span class="pre">size</span></code>,
<code class="docutils literal notranslate"><span class="pre">status</span></code>, <code class="docutils literal notranslate"><span class="pre">tags</span></code>, <code class="docutils literal notranslate"><span class="pre">urn</span></code>, <code class="docutils literal notranslate"><span class="pre">vcpus</span></code>, <code class="docutils literal notranslate"><span class="pre">volume_ids</span></code>, or <code class="docutils literal notranslate"><span class="pre">vpc_uuid</span></code>’.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">values</span></code> (<code class="docutils literal notranslate"><span class="pre">list</span></code>) - A list of values to match against the <code class="docutils literal notranslate"><span class="pre">key</span></code> field. Only retrieves Droplets
where the <code class="docutils literal notranslate"><span class="pre">key</span></code> field takes on one or more of the values provided here.</p></li>
</ul>
<p>The <strong>sorts</strong> object supports the following:</p>
<ul class="simple">
<li><p><code class="docutils literal notranslate"><span class="pre">direction</span></code> (<code class="docutils literal notranslate"><span class="pre">str</span></code>) - The sort direction. This may be either <code class="docutils literal notranslate"><span class="pre">asc</span></code> or <code class="docutils literal notranslate"><span class="pre">desc</span></code>.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">key</span></code> (<code class="docutils literal notranslate"><span class="pre">str</span></code>) - Sort the Droplets by this key. This may be one of <code class="docutils literal notranslate"><span class="pre">backups</span></code>, <code class="docutils literal notranslate"><span class="pre">created_at</span></code>, <code class="docutils literal notranslate"><span class="pre">disk</span></code>, <code class="docutils literal notranslate"><span class="pre">id</span></code>,
<code class="docutils literal notranslate"><span class="pre">image</span></code>, <code class="docutils literal notranslate"><span class="pre">ipv4_address</span></code>, <code class="docutils literal notranslate"><span class="pre">ipv4_address_private</span></code>, <code class="docutils literal notranslate"><span class="pre">ipv6</span></code>, <code class="docutils literal notranslate"><span class="pre">ipv6_address</span></code>, <code class="docutils literal notranslate"><span class="pre">ipv6_address_private</span></code>, <code class="docutils literal notranslate"><span class="pre">locked</span></code>,
<code class="docutils literal notranslate"><span class="pre">memory</span></code>, <code class="docutils literal notranslate"><span class="pre">monitoring</span></code>, <code class="docutils literal notranslate"><span class="pre">name</span></code>, <code class="docutils literal notranslate"><span class="pre">price_hourly</span></code>, <code class="docutils literal notranslate"><span class="pre">price_monthly</span></code>, <code class="docutils literal notranslate"><span class="pre">private_networking</span></code>, <code class="docutils literal notranslate"><span class="pre">region</span></code>, <code class="docutils literal notranslate"><span class="pre">size</span></code>,
<code class="docutils literal notranslate"><span class="pre">status</span></code>, <code class="docutils literal notranslate"><span class="pre">urn</span></code>, <code class="docutils literal notranslate"><span class="pre">vcpus</span></code>, or <code class="docutils literal notranslate"><span class="pre">vpc_uuid</span></code>.</p></li>
</ul>
</dd></dl>

<dl class="py function">
<dt id="pulumi_digitalocean.get_floating_ip">
<code class="sig-prename descclassname">pulumi_digitalocean.</code><code class="sig-name descname">get_floating_ip</code><span class="sig-paren">(</span><em class="sig-param"><span class="n">ip_address</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">opts</span><span class="o">=</span><span class="default_value">None</span></em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_digitalocean.get_floating_ip" title="Permalink to this definition">¶</a></dt>
<dd><p>Use this data source to access information about an existing resource.</p>
<dl class="field-list simple">
<dt class="field-odd">Parameters</dt>
<dd class="field-odd"><p><strong>ip_address</strong> (<em>str</em>) – The allocated IP address of the specific floating IP to retrieve.</p>
</dd>
</dl>
</dd></dl>

<dl class="py function">
<dt id="pulumi_digitalocean.get_image">
<code class="sig-prename descclassname">pulumi_digitalocean.</code><code class="sig-name descname">get_image</code><span class="sig-paren">(</span><em class="sig-param"><span class="n">id</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">name</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">slug</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">source</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">opts</span><span class="o">=</span><span class="default_value">None</span></em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_digitalocean.get_image" title="Permalink to this definition">¶</a></dt>
<dd><p>Use this data source to access information about an existing resource.</p>
<dl class="field-list simple">
<dt class="field-odd">Parameters</dt>
<dd class="field-odd"><ul class="simple">
<li><p><strong>id</strong> (<em>float</em>) – The id of the image</p></li>
<li><p><strong>name</strong> (<em>str</em>) – The name of the image.</p></li>
<li><p><strong>slug</strong> (<em>str</em>) – The slug of the official image.</p></li>
<li><p><strong>source</strong> (<em>str</em>) – Restrict the search to one of the following categories of images:</p></li>
</ul>
</dd>
</dl>
<div class="highlight-default notranslate"><div class="highlight"><pre><span></span>- `all` - All images (whether public or private)
- `applications` - One-click applications
- `distributions` - Distributions
- `user` - (Default) User (private) images
</pre></div>
</div>
</dd></dl>

<dl class="py function">
<dt id="pulumi_digitalocean.get_images">
<code class="sig-prename descclassname">pulumi_digitalocean.</code><code class="sig-name descname">get_images</code><span class="sig-paren">(</span><em class="sig-param"><span class="n">filters</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">sorts</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">opts</span><span class="o">=</span><span class="default_value">None</span></em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_digitalocean.get_images" title="Permalink to this definition">¶</a></dt>
<dd><p>Use this data source to access information about an existing resource.</p>
<dl class="field-list simple">
<dt class="field-odd">Parameters</dt>
<dd class="field-odd"><ul class="simple">
<li><p><strong>filters</strong> (<em>list</em>) – Filter the results.
The <code class="docutils literal notranslate"><span class="pre">filter</span></code> block is documented below.</p></li>
<li><p><strong>sorts</strong> (<em>list</em>) – Sort the results.
The <code class="docutils literal notranslate"><span class="pre">sort</span></code> block is documented below.</p></li>
</ul>
</dd>
</dl>
<p>The <strong>filters</strong> object supports the following:</p>
<ul class="simple">
<li><p><code class="docutils literal notranslate"><span class="pre">key</span></code> (<code class="docutils literal notranslate"><span class="pre">str</span></code>) - Filter the images by this key. This may be one of <code class="docutils literal notranslate"><span class="pre">distribution</span></code>, <code class="docutils literal notranslate"><span class="pre">error_message</span></code>,
<code class="docutils literal notranslate"><span class="pre">id</span></code>, <code class="docutils literal notranslate"><span class="pre">image</span></code>, <code class="docutils literal notranslate"><span class="pre">min_disk_size</span></code>, <code class="docutils literal notranslate"><span class="pre">name</span></code>, <code class="docutils literal notranslate"><span class="pre">private</span></code>, <code class="docutils literal notranslate"><span class="pre">regions</span></code>, <code class="docutils literal notranslate"><span class="pre">size_gigabytes</span></code>, <code class="docutils literal notranslate"><span class="pre">slug</span></code>, <code class="docutils literal notranslate"><span class="pre">status</span></code>,
<code class="docutils literal notranslate"><span class="pre">tags</span></code>, or <code class="docutils literal notranslate"><span class="pre">type</span></code>.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">values</span></code> (<code class="docutils literal notranslate"><span class="pre">list</span></code>) - A list of values to match against the <code class="docutils literal notranslate"><span class="pre">key</span></code> field. Only retrieves images
where the <code class="docutils literal notranslate"><span class="pre">key</span></code> field takes on one or more of the values provided here.</p></li>
</ul>
<p>The <strong>sorts</strong> object supports the following:</p>
<ul class="simple">
<li><p><code class="docutils literal notranslate"><span class="pre">direction</span></code> (<code class="docutils literal notranslate"><span class="pre">str</span></code>) - The sort direction. This may be either <code class="docutils literal notranslate"><span class="pre">asc</span></code> or <code class="docutils literal notranslate"><span class="pre">desc</span></code>.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">key</span></code> (<code class="docutils literal notranslate"><span class="pre">str</span></code>) - Sort the images by this key. This may be one of <code class="docutils literal notranslate"><span class="pre">distribution</span></code>, <code class="docutils literal notranslate"><span class="pre">error_message</span></code>, <code class="docutils literal notranslate"><span class="pre">id</span></code>,
<code class="docutils literal notranslate"><span class="pre">image</span></code>, <code class="docutils literal notranslate"><span class="pre">min_disk_size</span></code>, <code class="docutils literal notranslate"><span class="pre">name</span></code>, <code class="docutils literal notranslate"><span class="pre">private</span></code>, <code class="docutils literal notranslate"><span class="pre">size_gigabytes</span></code>, <code class="docutils literal notranslate"><span class="pre">slug</span></code>, <code class="docutils literal notranslate"><span class="pre">status</span></code>, or <code class="docutils literal notranslate"><span class="pre">type</span></code>.</p></li>
</ul>
</dd></dl>

<dl class="py function">
<dt id="pulumi_digitalocean.get_kubernetes_cluster">
<code class="sig-prename descclassname">pulumi_digitalocean.</code><code class="sig-name descname">get_kubernetes_cluster</code><span class="sig-paren">(</span><em class="sig-param"><span class="n">name</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">tags</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">opts</span><span class="o">=</span><span class="default_value">None</span></em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_digitalocean.get_kubernetes_cluster" title="Permalink to this definition">¶</a></dt>
<dd><p>Use this data source to access information about an existing resource.</p>
<dl class="field-list simple">
<dt class="field-odd">Parameters</dt>
<dd class="field-odd"><ul class="simple">
<li><p><strong>name</strong> (<em>str</em>) – The name of Kubernetes cluster.</p></li>
<li><p><strong>tags</strong> (<em>list</em>) – A list of tag names to be applied to the Kubernetes cluster.</p></li>
</ul>
</dd>
</dl>
</dd></dl>

<dl class="py function">
<dt id="pulumi_digitalocean.get_kubernetes_versions">
<code class="sig-prename descclassname">pulumi_digitalocean.</code><code class="sig-name descname">get_kubernetes_versions</code><span class="sig-paren">(</span><em class="sig-param"><span class="n">version_prefix</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">opts</span><span class="o">=</span><span class="default_value">None</span></em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_digitalocean.get_kubernetes_versions" title="Permalink to this definition">¶</a></dt>
<dd><p>Provides access to the available DigitalOcean Kubernetes Service versions.</p>
<div class="highlight-python notranslate"><div class="highlight"><pre><span></span><span class="kn">import</span> <span class="nn">pulumi</span>
<span class="kn">import</span> <span class="nn">pulumi_digitalocean</span> <span class="k">as</span> <span class="nn">digitalocean</span>

<span class="n">example</span> <span class="o">=</span> <span class="n">digitalocean</span><span class="o">.</span><span class="n">get_kubernetes_versions</span><span class="p">()</span>
<span class="n">pulumi</span><span class="o">.</span><span class="n">export</span><span class="p">(</span><span class="s2">&quot;k8s-versions&quot;</span><span class="p">,</span> <span class="n">example</span><span class="o">.</span><span class="n">valid_versions</span><span class="p">)</span>
</pre></div>
</div>
<div class="highlight-python notranslate"><div class="highlight"><pre><span></span><span class="kn">import</span> <span class="nn">pulumi</span>
<span class="kn">import</span> <span class="nn">pulumi_digitalocean</span> <span class="k">as</span> <span class="nn">digitalocean</span>

<span class="n">example</span> <span class="o">=</span> <span class="n">digitalocean</span><span class="o">.</span><span class="n">get_kubernetes_versions</span><span class="p">()</span>
<span class="n">example_cluster</span> <span class="o">=</span> <span class="n">digitalocean</span><span class="o">.</span><span class="n">KubernetesCluster</span><span class="p">(</span><span class="s2">&quot;example-cluster&quot;</span><span class="p">,</span>
    <span class="n">region</span><span class="o">=</span><span class="s2">&quot;lon1&quot;</span><span class="p">,</span>
    <span class="n">version</span><span class="o">=</span><span class="n">example</span><span class="o">.</span><span class="n">latest_version</span><span class="p">,</span>
    <span class="n">node_pool</span><span class="o">=</span><span class="p">{</span>
        <span class="s2">&quot;name&quot;</span><span class="p">:</span> <span class="s2">&quot;default&quot;</span><span class="p">,</span>
        <span class="s2">&quot;size&quot;</span><span class="p">:</span> <span class="s2">&quot;s-1vcpu-2gb&quot;</span><span class="p">,</span>
        <span class="s2">&quot;nodeCount&quot;</span><span class="p">:</span> <span class="mi">3</span><span class="p">,</span>
    <span class="p">})</span>
</pre></div>
</div>
<div class="highlight-python notranslate"><div class="highlight"><pre><span></span><span class="kn">import</span> <span class="nn">pulumi</span>
<span class="kn">import</span> <span class="nn">pulumi_digitalocean</span> <span class="k">as</span> <span class="nn">digitalocean</span>

<span class="n">example</span> <span class="o">=</span> <span class="n">digitalocean</span><span class="o">.</span><span class="n">get_kubernetes_versions</span><span class="p">(</span><span class="n">version_prefix</span><span class="o">=</span><span class="s2">&quot;1.16.&quot;</span><span class="p">)</span>
<span class="n">example_cluster</span> <span class="o">=</span> <span class="n">digitalocean</span><span class="o">.</span><span class="n">KubernetesCluster</span><span class="p">(</span><span class="s2">&quot;example-cluster&quot;</span><span class="p">,</span>
    <span class="n">region</span><span class="o">=</span><span class="s2">&quot;lon1&quot;</span><span class="p">,</span>
    <span class="n">version</span><span class="o">=</span><span class="n">example</span><span class="o">.</span><span class="n">latest_version</span><span class="p">,</span>
    <span class="n">node_pool</span><span class="o">=</span><span class="p">{</span>
        <span class="s2">&quot;name&quot;</span><span class="p">:</span> <span class="s2">&quot;default&quot;</span><span class="p">,</span>
        <span class="s2">&quot;size&quot;</span><span class="p">:</span> <span class="s2">&quot;s-1vcpu-2gb&quot;</span><span class="p">,</span>
        <span class="s2">&quot;nodeCount&quot;</span><span class="p">:</span> <span class="mi">3</span><span class="p">,</span>
    <span class="p">})</span>
</pre></div>
</div>
</dd></dl>

<dl class="py function">
<dt id="pulumi_digitalocean.get_load_balancer">
<code class="sig-prename descclassname">pulumi_digitalocean.</code><code class="sig-name descname">get_load_balancer</code><span class="sig-paren">(</span><em class="sig-param"><span class="n">name</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">opts</span><span class="o">=</span><span class="default_value">None</span></em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_digitalocean.get_load_balancer" title="Permalink to this definition">¶</a></dt>
<dd><p>Use this data source to access information about an existing resource.</p>
<dl class="field-list simple">
<dt class="field-odd">Parameters</dt>
<dd class="field-odd"><p><strong>name</strong> (<em>str</em>) – The name of load balancer.</p>
</dd>
</dl>
</dd></dl>

<dl class="py function">
<dt id="pulumi_digitalocean.get_project">
<code class="sig-prename descclassname">pulumi_digitalocean.</code><code class="sig-name descname">get_project</code><span class="sig-paren">(</span><em class="sig-param"><span class="n">id</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">name</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">opts</span><span class="o">=</span><span class="default_value">None</span></em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_digitalocean.get_project" title="Permalink to this definition">¶</a></dt>
<dd><p>Get information on a single DigitalOcean project. If neither the <code class="docutils literal notranslate"><span class="pre">id</span></code> nor <code class="docutils literal notranslate"><span class="pre">name</span></code> attributes are provided,
then this data source returns the default project.</p>
<div class="highlight-python notranslate"><div class="highlight"><pre><span></span><span class="kn">import</span> <span class="nn">pulumi</span>
<span class="kn">import</span> <span class="nn">pulumi_digitalocean</span> <span class="k">as</span> <span class="nn">digitalocean</span>

<span class="n">default</span> <span class="o">=</span> <span class="n">digitalocean</span><span class="o">.</span><span class="n">get_project</span><span class="p">()</span>
<span class="n">staging</span> <span class="o">=</span> <span class="n">digitalocean</span><span class="o">.</span><span class="n">get_project</span><span class="p">(</span><span class="n">name</span><span class="o">=</span><span class="s2">&quot;My Staging Project&quot;</span><span class="p">)</span>
</pre></div>
</div>
<dl class="field-list simple">
<dt class="field-odd">Parameters</dt>
<dd class="field-odd"><ul class="simple">
<li><p><strong>id</strong> (<em>str</em>) – the ID of the project to retrieve</p></li>
<li><p><strong>name</strong> (<em>str</em>) – the name of the project to retrieve. The data source will raise an error if more than
one project has the provided name or if no project has that name.</p></li>
</ul>
</dd>
</dl>
</dd></dl>

<dl class="py function">
<dt id="pulumi_digitalocean.get_projects">
<code class="sig-prename descclassname">pulumi_digitalocean.</code><code class="sig-name descname">get_projects</code><span class="sig-paren">(</span><em class="sig-param"><span class="n">filters</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">sorts</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">opts</span><span class="o">=</span><span class="default_value">None</span></em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_digitalocean.get_projects" title="Permalink to this definition">¶</a></dt>
<dd><p>Retrieve information about all DigitalOcean projects associated with an account, with
the ability to filter and sort the results. If no filters are specified, all projects
will be returned.</p>
<p>Note: You can use the <cite>`</cite>.Project`` &lt;<a class="reference external" href="https://www.terraform.io/docs/providers/do/d/project.html">https://www.terraform.io/docs/providers/do/d/project.html</a>&gt;`_ data source to
obtain metadata about a single project if you already know the <code class="docutils literal notranslate"><span class="pre">id</span></code> to retrieve or the unique
<code class="docutils literal notranslate"><span class="pre">name</span></code> of the project.</p>
<div class="highlight-python notranslate"><div class="highlight"><pre><span></span><span class="kn">import</span> <span class="nn">pulumi</span>
<span class="kn">import</span> <span class="nn">pulumi_digitalocean</span> <span class="k">as</span> <span class="nn">digitalocean</span>

<span class="n">staging</span> <span class="o">=</span> <span class="n">digitalocean</span><span class="o">.</span><span class="n">get_projects</span><span class="p">(</span><span class="n">filters</span><span class="o">=</span><span class="p">[{</span>
    <span class="s2">&quot;key&quot;</span><span class="p">:</span> <span class="s2">&quot;environment&quot;</span><span class="p">,</span>
    <span class="s2">&quot;values&quot;</span><span class="p">:</span> <span class="p">[</span><span class="s2">&quot;Staging&quot;</span><span class="p">],</span>
<span class="p">}])</span>
</pre></div>
</div>
<dl class="field-list simple">
<dt class="field-odd">Parameters</dt>
<dd class="field-odd"><ul class="simple">
<li><p><strong>filters</strong> (<em>list</em>) – Filter the results.
The <code class="docutils literal notranslate"><span class="pre">filter</span></code> block is documented below.</p></li>
<li><p><strong>sorts</strong> (<em>list</em>) – Sort the results.
The <code class="docutils literal notranslate"><span class="pre">sort</span></code> block is documented below.</p></li>
</ul>
</dd>
</dl>
<p>The <strong>filters</strong> object supports the following:</p>
<ul class="simple">
<li><p><code class="docutils literal notranslate"><span class="pre">key</span></code> (<code class="docutils literal notranslate"><span class="pre">str</span></code>) - Filter the projects by this key. This may be one of <code class="docutils literal notranslate"><span class="pre">name</span></code>,
<code class="docutils literal notranslate"><span class="pre">purpose</span></code>, <code class="docutils literal notranslate"><span class="pre">description</span></code>, <code class="docutils literal notranslate"><span class="pre">environment</span></code>, or <code class="docutils literal notranslate"><span class="pre">is_default</span></code>.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">values</span></code> (<code class="docutils literal notranslate"><span class="pre">list</span></code>) - A list of values to match against the <code class="docutils literal notranslate"><span class="pre">key</span></code> field. Only retrieves projects
where the <code class="docutils literal notranslate"><span class="pre">key</span></code> field takes on one or more of the values provided here.</p></li>
</ul>
<p>The <strong>sorts</strong> object supports the following:</p>
<ul class="simple">
<li><p><code class="docutils literal notranslate"><span class="pre">direction</span></code> (<code class="docutils literal notranslate"><span class="pre">str</span></code>) - The sort direction. This may be either <code class="docutils literal notranslate"><span class="pre">asc</span></code> or <code class="docutils literal notranslate"><span class="pre">desc</span></code>.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">key</span></code> (<code class="docutils literal notranslate"><span class="pre">str</span></code>) - Sort the projects by this key. This may be one of <code class="docutils literal notranslate"><span class="pre">name</span></code>,
<code class="docutils literal notranslate"><span class="pre">purpose</span></code>, <code class="docutils literal notranslate"><span class="pre">description</span></code>, or <code class="docutils literal notranslate"><span class="pre">environment</span></code>.</p></li>
</ul>
</dd></dl>

<dl class="py function">
<dt id="pulumi_digitalocean.get_record">
<code class="sig-prename descclassname">pulumi_digitalocean.</code><code class="sig-name descname">get_record</code><span class="sig-paren">(</span><em class="sig-param"><span class="n">domain</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">name</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">opts</span><span class="o">=</span><span class="default_value">None</span></em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_digitalocean.get_record" title="Permalink to this definition">¶</a></dt>
<dd><p>Use this data source to access information about an existing resource.</p>
<dl class="field-list simple">
<dt class="field-odd">Parameters</dt>
<dd class="field-odd"><ul class="simple">
<li><p><strong>domain</strong> (<em>str</em>) – The domain name of the record.</p></li>
<li><p><strong>name</strong> (<em>str</em>) – The name of the record.</p></li>
</ul>
</dd>
</dl>
</dd></dl>

<dl class="py function">
<dt id="pulumi_digitalocean.get_region">
<code class="sig-prename descclassname">pulumi_digitalocean.</code><code class="sig-name descname">get_region</code><span class="sig-paren">(</span><em class="sig-param"><span class="n">slug</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">opts</span><span class="o">=</span><span class="default_value">None</span></em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_digitalocean.get_region" title="Permalink to this definition">¶</a></dt>
<dd><p>Get information on a single DigitalOcean region. This is useful to find out 
what Droplet sizes and features are supported within a region.</p>
<div class="highlight-python notranslate"><div class="highlight"><pre><span></span><span class="kn">import</span> <span class="nn">pulumi</span>
<span class="kn">import</span> <span class="nn">pulumi_digitalocean</span> <span class="k">as</span> <span class="nn">digitalocean</span>

<span class="n">sfo2</span> <span class="o">=</span> <span class="n">digitalocean</span><span class="o">.</span><span class="n">get_region</span><span class="p">(</span><span class="n">slug</span><span class="o">=</span><span class="s2">&quot;sfo2&quot;</span><span class="p">)</span>
<span class="n">pulumi</span><span class="o">.</span><span class="n">export</span><span class="p">(</span><span class="s2">&quot;regionName&quot;</span><span class="p">,</span> <span class="n">sfo2</span><span class="o">.</span><span class="n">name</span><span class="p">)</span>
</pre></div>
</div>
<dl class="field-list simple">
<dt class="field-odd">Parameters</dt>
<dd class="field-odd"><p><strong>slug</strong> (<em>str</em>) – A human-readable string that is used as a unique identifier for each region.</p>
</dd>
</dl>
</dd></dl>

<dl class="py function">
<dt id="pulumi_digitalocean.get_regions">
<code class="sig-prename descclassname">pulumi_digitalocean.</code><code class="sig-name descname">get_regions</code><span class="sig-paren">(</span><em class="sig-param"><span class="n">filters</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">sorts</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">opts</span><span class="o">=</span><span class="default_value">None</span></em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_digitalocean.get_regions" title="Permalink to this definition">¶</a></dt>
<dd><p>Retrieve information about all supported DigitalOcean regions, with the ability to
filter and sort the results. If no filters are specified, all regions will be returned.</p>
<p>Note: You can use the <cite>`</cite>.getRegion`` &lt;<a class="reference external" href="https://www.terraform.io/docs/providers/do/d/region.html">https://www.terraform.io/docs/providers/do/d/region.html</a>&gt;`_ data source
to obtain metadata about a single region if you already know the <code class="docutils literal notranslate"><span class="pre">slug</span></code> to retrieve.</p>
<div class="highlight-python notranslate"><div class="highlight"><pre><span></span><span class="kn">import</span> <span class="nn">pulumi</span>
<span class="kn">import</span> <span class="nn">pulumi_digitalocean</span> <span class="k">as</span> <span class="nn">digitalocean</span>

<span class="n">available</span> <span class="o">=</span> <span class="n">digitalocean</span><span class="o">.</span><span class="n">get_regions</span><span class="p">(</span><span class="n">filters</span><span class="o">=</span><span class="p">[{</span>
    <span class="s2">&quot;key&quot;</span><span class="p">:</span> <span class="s2">&quot;available&quot;</span><span class="p">,</span>
    <span class="s2">&quot;values&quot;</span><span class="p">:</span> <span class="p">[</span><span class="s2">&quot;true&quot;</span><span class="p">],</span>
<span class="p">}])</span>
</pre></div>
</div>
<dl class="field-list simple">
<dt class="field-odd">Parameters</dt>
<dd class="field-odd"><ul class="simple">
<li><p><strong>filters</strong> (<em>list</em>) – Filter the results.
The <code class="docutils literal notranslate"><span class="pre">filter</span></code> block is documented below.</p></li>
<li><p><strong>sorts</strong> (<em>list</em>) – Sort the results.
The <code class="docutils literal notranslate"><span class="pre">sort</span></code> block is documented below.</p></li>
</ul>
</dd>
</dl>
<p>The <strong>filters</strong> object supports the following:</p>
<ul class="simple">
<li><p><code class="docutils literal notranslate"><span class="pre">key</span></code> (<code class="docutils literal notranslate"><span class="pre">str</span></code>) - Filter the regions by this key. This may be one of <code class="docutils literal notranslate"><span class="pre">slug</span></code>,
<code class="docutils literal notranslate"><span class="pre">name</span></code>, <code class="docutils literal notranslate"><span class="pre">available</span></code>, <code class="docutils literal notranslate"><span class="pre">features</span></code>, or <code class="docutils literal notranslate"><span class="pre">sizes</span></code>.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">values</span></code> (<code class="docutils literal notranslate"><span class="pre">list</span></code>) - A list of values to match against the <code class="docutils literal notranslate"><span class="pre">key</span></code> field. Only retrieves regions
where the <code class="docutils literal notranslate"><span class="pre">key</span></code> field takes on one or more of the values provided here.</p></li>
</ul>
<p>The <strong>sorts</strong> object supports the following:</p>
<ul class="simple">
<li><p><code class="docutils literal notranslate"><span class="pre">direction</span></code> (<code class="docutils literal notranslate"><span class="pre">str</span></code>) - The sort direction. This may be either <code class="docutils literal notranslate"><span class="pre">asc</span></code> or <code class="docutils literal notranslate"><span class="pre">desc</span></code>.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">key</span></code> (<code class="docutils literal notranslate"><span class="pre">str</span></code>) - Sort the regions by this key. This may be one of <code class="docutils literal notranslate"><span class="pre">slug</span></code>,
<code class="docutils literal notranslate"><span class="pre">name</span></code>, or <code class="docutils literal notranslate"><span class="pre">available</span></code>.</p></li>
</ul>
</dd></dl>

<dl class="py function">
<dt id="pulumi_digitalocean.get_sizes">
<code class="sig-prename descclassname">pulumi_digitalocean.</code><code class="sig-name descname">get_sizes</code><span class="sig-paren">(</span><em class="sig-param"><span class="n">filters</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">sorts</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">opts</span><span class="o">=</span><span class="default_value">None</span></em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_digitalocean.get_sizes" title="Permalink to this definition">¶</a></dt>
<dd><p>Retrieves information about the Droplet sizes that DigitalOcean supports, with
the ability to filter and sort the results. If no filters are specified, all sizes
will be returned.</p>
<div class="highlight-python notranslate"><div class="highlight"><pre><span></span><span class="kn">import</span> <span class="nn">pulumi</span>
<span class="kn">import</span> <span class="nn">pulumi_digitalocean</span> <span class="k">as</span> <span class="nn">digitalocean</span>

<span class="n">main</span> <span class="o">=</span> <span class="n">digitalocean</span><span class="o">.</span><span class="n">get_sizes</span><span class="p">(</span><span class="nb">filter</span><span class="o">=</span><span class="p">[{</span>
    <span class="s2">&quot;key&quot;</span><span class="p">:</span> <span class="s2">&quot;slug&quot;</span><span class="p">,</span>
    <span class="s2">&quot;values&quot;</span><span class="p">:</span> <span class="p">[</span><span class="s2">&quot;s-1vcpu-1gb&quot;</span><span class="p">],</span>
<span class="p">}])</span>
<span class="n">web</span> <span class="o">=</span> <span class="n">digitalocean</span><span class="o">.</span><span class="n">Droplet</span><span class="p">(</span><span class="s2">&quot;web&quot;</span><span class="p">,</span>
    <span class="n">image</span><span class="o">=</span><span class="s2">&quot;ubuntu-18-04-x64&quot;</span><span class="p">,</span>
    <span class="n">region</span><span class="o">=</span><span class="s2">&quot;sgp1&quot;</span><span class="p">,</span>
    <span class="n">size</span><span class="o">=</span><span class="n">main</span><span class="o">.</span><span class="n">sizes</span><span class="p">[</span><span class="mi">0</span><span class="p">][</span><span class="s2">&quot;slug&quot;</span><span class="p">])</span>
</pre></div>
</div>
<dl class="field-list simple">
<dt class="field-odd">Parameters</dt>
<dd class="field-odd"><ul class="simple">
<li><p><strong>filters</strong> (<em>list</em>) – Filter the results.
The <code class="docutils literal notranslate"><span class="pre">filter</span></code> block is documented below.</p></li>
<li><p><strong>sorts</strong> (<em>list</em>) – Sort the results.
The <code class="docutils literal notranslate"><span class="pre">sort</span></code> block is documented below.</p></li>
</ul>
</dd>
</dl>
<p>The <strong>filters</strong> object supports the following:</p>
<ul class="simple">
<li><p><code class="docutils literal notranslate"><span class="pre">key</span></code> (<code class="docutils literal notranslate"><span class="pre">str</span></code>) - Filter the sizes by this key. This may be one of <code class="docutils literal notranslate"><span class="pre">slug</span></code>,
<code class="docutils literal notranslate"><span class="pre">regions</span></code>, <code class="docutils literal notranslate"><span class="pre">memory</span></code>, <code class="docutils literal notranslate"><span class="pre">vcpus</span></code>, <code class="docutils literal notranslate"><span class="pre">disk</span></code>, <code class="docutils literal notranslate"><span class="pre">transfer</span></code>, <code class="docutils literal notranslate"><span class="pre">price_monthly</span></code>,
<code class="docutils literal notranslate"><span class="pre">price_hourly</span></code>, or <code class="docutils literal notranslate"><span class="pre">available</span></code>.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">values</span></code> (<code class="docutils literal notranslate"><span class="pre">list</span></code>) - Only retrieves images which keys has value that matches
one of the values provided here.</p></li>
</ul>
<p>The <strong>sorts</strong> object supports the following:</p>
<ul class="simple">
<li><p><code class="docutils literal notranslate"><span class="pre">direction</span></code> (<code class="docutils literal notranslate"><span class="pre">str</span></code>) - The sort direction. This may be either <code class="docutils literal notranslate"><span class="pre">asc</span></code> or <code class="docutils literal notranslate"><span class="pre">desc</span></code>.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">key</span></code> (<code class="docutils literal notranslate"><span class="pre">str</span></code>) - Sort the sizes by this key. This may be one of <code class="docutils literal notranslate"><span class="pre">slug</span></code>,
<code class="docutils literal notranslate"><span class="pre">memory</span></code>, <code class="docutils literal notranslate"><span class="pre">vcpus</span></code>, <code class="docutils literal notranslate"><span class="pre">disk</span></code>, <code class="docutils literal notranslate"><span class="pre">transfer</span></code>, <code class="docutils literal notranslate"><span class="pre">price_monthly</span></code>, or <code class="docutils literal notranslate"><span class="pre">price_hourly</span></code>.</p></li>
</ul>
</dd></dl>

<dl class="py function">
<dt id="pulumi_digitalocean.get_spaces_bucket">
<code class="sig-prename descclassname">pulumi_digitalocean.</code><code class="sig-name descname">get_spaces_bucket</code><span class="sig-paren">(</span><em class="sig-param"><span class="n">name</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">region</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">opts</span><span class="o">=</span><span class="default_value">None</span></em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_digitalocean.get_spaces_bucket" title="Permalink to this definition">¶</a></dt>
<dd><p>Use this data source to access information about an existing resource.</p>
<dl class="field-list simple">
<dt class="field-odd">Parameters</dt>
<dd class="field-odd"><ul class="simple">
<li><p><strong>name</strong> (<em>str</em>) – The name of the Spaces bucket.</p></li>
<li><p><strong>region</strong> (<em>str</em>) – The slug of the region where the bucket is stored.</p></li>
</ul>
</dd>
</dl>
</dd></dl>

<dl class="py function">
<dt id="pulumi_digitalocean.get_spaces_bucket_object">
<code class="sig-prename descclassname">pulumi_digitalocean.</code><code class="sig-name descname">get_spaces_bucket_object</code><span class="sig-paren">(</span><em class="sig-param"><span class="n">bucket</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">key</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">range</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">region</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">version_id</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">opts</span><span class="o">=</span><span class="default_value">None</span></em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_digitalocean.get_spaces_bucket_object" title="Permalink to this definition">¶</a></dt>
<dd><p>The Spaces object data source allows access to the metadata and
<em>optionally</em> (see below) content of an object stored inside a Spaces bucket.</p>
<blockquote>
<div><p><strong>Note:</strong> The content of an object (<code class="docutils literal notranslate"><span class="pre">body</span></code> field) is available only for objects which have a human-readable
<code class="docutils literal notranslate"><span class="pre">Content-Type</span></code> (<code class="docutils literal notranslate"><span class="pre">text/*</span></code> and <code class="docutils literal notranslate"><span class="pre">application/json</span></code>). This is to prevent printing unsafe characters and potentially
downloading large amount of data which would be thrown away in favor of metadata.</p>
</div></blockquote>
<div class="highlight-python notranslate"><div class="highlight"><pre><span></span><span class="kn">import</span> <span class="nn">pulumi</span>
<span class="kn">import</span> <span class="nn">pulumi_digitalocean</span> <span class="k">as</span> <span class="nn">digitalocean</span>

<span class="n">bootstrap_script</span> <span class="o">=</span> <span class="n">digitalocean</span><span class="o">.</span><span class="n">get_spaces_bucket_object</span><span class="p">(</span><span class="n">bucket</span><span class="o">=</span><span class="s2">&quot;ourcorp-deploy-config&quot;</span><span class="p">,</span>
    <span class="n">region</span><span class="o">=</span><span class="s2">&quot;nyc3&quot;</span><span class="p">,</span>
    <span class="n">key</span><span class="o">=</span><span class="s2">&quot;droplet-bootstrap-script.sh&quot;</span><span class="p">)</span>
<span class="n">web</span> <span class="o">=</span> <span class="n">digitalocean</span><span class="o">.</span><span class="n">Droplet</span><span class="p">(</span><span class="s2">&quot;web&quot;</span><span class="p">,</span>
    <span class="n">image</span><span class="o">=</span><span class="s2">&quot;ubuntu-18-04-x64&quot;</span><span class="p">,</span>
    <span class="n">region</span><span class="o">=</span><span class="s2">&quot;nyc2&quot;</span><span class="p">,</span>
    <span class="n">size</span><span class="o">=</span><span class="s2">&quot;s-1vcpu-1gb&quot;</span><span class="p">,</span>
    <span class="n">user_data</span><span class="o">=</span><span class="n">bootstrap_script</span><span class="o">.</span><span class="n">body</span><span class="p">)</span>
</pre></div>
</div>
<dl class="field-list simple">
<dt class="field-odd">Parameters</dt>
<dd class="field-odd"><ul class="simple">
<li><p><strong>bucket</strong> (<em>str</em>) – The name of the bucket to read the object from.</p></li>
<li><p><strong>key</strong> (<em>str</em>) – The full path to the object inside the bucket</p></li>
<li><p><strong>region</strong> (<em>str</em>) – The slug of the region where the bucket is stored.</p></li>
<li><p><strong>version_id</strong> (<em>str</em>) – Specific version ID of the object returned (defaults to latest version)</p></li>
</ul>
</dd>
</dl>
</dd></dl>

<dl class="py function">
<dt id="pulumi_digitalocean.get_spaces_bucket_objects">
<code class="sig-prename descclassname">pulumi_digitalocean.</code><code class="sig-name descname">get_spaces_bucket_objects</code><span class="sig-paren">(</span><em class="sig-param"><span class="n">bucket</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">delimiter</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">encoding_type</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">max_keys</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">prefix</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">region</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">opts</span><span class="o">=</span><span class="default_value">None</span></em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_digitalocean.get_spaces_bucket_objects" title="Permalink to this definition">¶</a></dt>
<dd><p>Use this data source to access information about an existing resource.</p>
<dl class="field-list simple">
<dt class="field-odd">Parameters</dt>
<dd class="field-odd"><ul class="simple">
<li><p><strong>bucket</strong> (<em>str</em>) – Lists object keys in this Spaces bucket</p></li>
<li><p><strong>delimiter</strong> (<em>str</em>) – A character used to group keys (Default: none)</p></li>
<li><p><strong>encoding_type</strong> (<em>str</em>) – Encodes keys using this method (Default: none; besides none, only “url” can be used)</p></li>
<li><p><strong>max_keys</strong> (<em>float</em>) – Maximum object keys to return (Default: 1000)</p></li>
<li><p><strong>prefix</strong> (<em>str</em>) – Limits results to object keys with this prefix (Default: none)</p></li>
<li><p><strong>region</strong> (<em>str</em>) – The slug of the region where the bucket is stored.</p></li>
</ul>
</dd>
</dl>
</dd></dl>

<dl class="py function">
<dt id="pulumi_digitalocean.get_spaces_buckets">
<code class="sig-prename descclassname">pulumi_digitalocean.</code><code class="sig-name descname">get_spaces_buckets</code><span class="sig-paren">(</span><em class="sig-param"><span class="n">filters</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">sorts</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">opts</span><span class="o">=</span><span class="default_value">None</span></em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_digitalocean.get_spaces_buckets" title="Permalink to this definition">¶</a></dt>
<dd><p>Get information on Spaces buckets for use in other resources, with the ability to filter and sort the results.
If no filters are specified, all Spaces buckets will be returned.</p>
<p>Note: You can use the <cite>`</cite>.SpacesBucket`` &lt;<a class="reference external" href="https://www.terraform.io/docs/providers/do/d/spaces_bucket.html">https://www.terraform.io/docs/providers/do/d/spaces_bucket.html</a>&gt;`_ data source to
obtain metadata about a single bucket if you already know its <code class="docutils literal notranslate"><span class="pre">name</span></code> and <code class="docutils literal notranslate"><span class="pre">region</span></code>.</p>
<div class="highlight-python notranslate"><div class="highlight"><pre><span></span><span class="kn">import</span> <span class="nn">pulumi</span>
<span class="kn">import</span> <span class="nn">pulumi_digitalocean</span> <span class="k">as</span> <span class="nn">digitalocean</span>

<span class="n">nyc3</span> <span class="o">=</span> <span class="n">digitalocean</span><span class="o">.</span><span class="n">get_spaces_buckets</span><span class="p">(</span><span class="n">filters</span><span class="o">=</span><span class="p">[{</span>
    <span class="s2">&quot;key&quot;</span><span class="p">:</span> <span class="s2">&quot;region&quot;</span><span class="p">,</span>
    <span class="s2">&quot;values&quot;</span><span class="p">:</span> <span class="p">[</span><span class="s2">&quot;nyc3&quot;</span><span class="p">],</span>
<span class="p">}])</span>
</pre></div>
</div>
<dl class="field-list simple">
<dt class="field-odd">Parameters</dt>
<dd class="field-odd"><ul class="simple">
<li><p><strong>filters</strong> (<em>list</em>) – Filter the results.
The <code class="docutils literal notranslate"><span class="pre">filter</span></code> block is documented below.</p></li>
<li><p><strong>sorts</strong> (<em>list</em>) – Sort the results.
The <code class="docutils literal notranslate"><span class="pre">sort</span></code> block is documented below.</p></li>
</ul>
</dd>
</dl>
<p>The <strong>filters</strong> object supports the following:</p>
<ul class="simple">
<li><p><code class="docutils literal notranslate"><span class="pre">key</span></code> (<code class="docutils literal notranslate"><span class="pre">str</span></code>) - Filter the images by this key. This may be one of <code class="docutils literal notranslate"><span class="pre">bucket_domain_name</span></code>, <code class="docutils literal notranslate"><span class="pre">name</span></code>, <code class="docutils literal notranslate"><span class="pre">region</span></code>, or <code class="docutils literal notranslate"><span class="pre">urn</span></code>.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">values</span></code> (<code class="docutils literal notranslate"><span class="pre">list</span></code>) - A list of values to match against the <code class="docutils literal notranslate"><span class="pre">key</span></code> field. Only retrieves images
where the <code class="docutils literal notranslate"><span class="pre">key</span></code> field takes on one or more of the values provided here.</p></li>
</ul>
<p>The <strong>sorts</strong> object supports the following:</p>
<ul class="simple">
<li><p><code class="docutils literal notranslate"><span class="pre">direction</span></code> (<code class="docutils literal notranslate"><span class="pre">str</span></code>) - The sort direction. This may be either <code class="docutils literal notranslate"><span class="pre">asc</span></code> or <code class="docutils literal notranslate"><span class="pre">desc</span></code>.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">key</span></code> (<code class="docutils literal notranslate"><span class="pre">str</span></code>) - Sort the images by this key. This may be one of <code class="docutils literal notranslate"><span class="pre">bucket_domain_name</span></code>, <code class="docutils literal notranslate"><span class="pre">name</span></code>, <code class="docutils literal notranslate"><span class="pre">region</span></code>, or <code class="docutils literal notranslate"><span class="pre">urn</span></code>.</p></li>
</ul>
</dd></dl>

<dl class="py function">
<dt id="pulumi_digitalocean.get_ssh_key">
<code class="sig-prename descclassname">pulumi_digitalocean.</code><code class="sig-name descname">get_ssh_key</code><span class="sig-paren">(</span><em class="sig-param"><span class="n">name</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">opts</span><span class="o">=</span><span class="default_value">None</span></em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_digitalocean.get_ssh_key" title="Permalink to this definition">¶</a></dt>
<dd><p>Use this data source to access information about an existing resource.</p>
<dl class="field-list simple">
<dt class="field-odd">Parameters</dt>
<dd class="field-odd"><p><strong>name</strong> (<em>str</em>) – The name of the ssh key.</p>
</dd>
</dl>
</dd></dl>

<dl class="py function">
<dt id="pulumi_digitalocean.get_tag">
<code class="sig-prename descclassname">pulumi_digitalocean.</code><code class="sig-name descname">get_tag</code><span class="sig-paren">(</span><em class="sig-param"><span class="n">name</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">opts</span><span class="o">=</span><span class="default_value">None</span></em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_digitalocean.get_tag" title="Permalink to this definition">¶</a></dt>
<dd><p>Use this data source to access information about an existing resource.</p>
<dl class="field-list simple">
<dt class="field-odd">Parameters</dt>
<dd class="field-odd"><p><strong>name</strong> (<em>str</em>) – The name of the tag.</p>
</dd>
</dl>
</dd></dl>

<dl class="py function">
<dt id="pulumi_digitalocean.get_volume">
<code class="sig-prename descclassname">pulumi_digitalocean.</code><code class="sig-name descname">get_volume</code><span class="sig-paren">(</span><em class="sig-param"><span class="n">description</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">name</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">region</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">opts</span><span class="o">=</span><span class="default_value">None</span></em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_digitalocean.get_volume" title="Permalink to this definition">¶</a></dt>
<dd><p>Use this data source to access information about an existing resource.</p>
<dl class="field-list simple">
<dt class="field-odd">Parameters</dt>
<dd class="field-odd"><ul class="simple">
<li><p><strong>description</strong> (<em>str</em>) – Text describing a block storage volume.</p></li>
<li><p><strong>name</strong> (<em>str</em>) – The name of block storage volume.</p></li>
<li><p><strong>region</strong> (<em>str</em>) – The region the block storage volume is provisioned in.</p></li>
</ul>
</dd>
</dl>
</dd></dl>

<dl class="py function">
<dt id="pulumi_digitalocean.get_volume_snapshot">
<code class="sig-prename descclassname">pulumi_digitalocean.</code><code class="sig-name descname">get_volume_snapshot</code><span class="sig-paren">(</span><em class="sig-param"><span class="n">most_recent</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">name</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">name_regex</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">region</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">opts</span><span class="o">=</span><span class="default_value">None</span></em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_digitalocean.get_volume_snapshot" title="Permalink to this definition">¶</a></dt>
<dd><p>Volume snapshots are saved instances of a block storage volume. Use this data
source to retrieve the ID of a DigitalOcean volume snapshot for use in other
resources.</p>
<div class="highlight-python notranslate"><div class="highlight"><pre><span></span><span class="kn">import</span> <span class="nn">pulumi</span>
<span class="kn">import</span> <span class="nn">pulumi_digitalocean</span> <span class="k">as</span> <span class="nn">digitalocean</span>

<span class="n">snapshot</span> <span class="o">=</span> <span class="n">digitalocean</span><span class="o">.</span><span class="n">get_volume_snapshot</span><span class="p">(</span><span class="n">most_recent</span><span class="o">=</span><span class="kc">True</span><span class="p">,</span>
    <span class="n">name_regex</span><span class="o">=</span><span class="s2">&quot;^web&quot;</span><span class="p">,</span>
    <span class="n">region</span><span class="o">=</span><span class="s2">&quot;nyc3&quot;</span><span class="p">)</span>
</pre></div>
</div>
<dl class="field-list simple">
<dt class="field-odd">Parameters</dt>
<dd class="field-odd"><ul class="simple">
<li><p><strong>most_recent</strong> (<em>bool</em>) – If more than one result is returned, use the most recent volume snapshot.</p></li>
<li><p><strong>name</strong> (<em>str</em>) – The name of the volume snapshot.</p></li>
<li><p><strong>name_regex</strong> (<em>str</em>) – A regex string to apply to the volume snapshot list returned by DigitalOcean. This allows more advanced filtering not supported from the DigitalOcean API. This filtering is done locally on what DigitalOcean returns.</p></li>
<li><p><strong>region</strong> (<em>str</em>) – A “slug” representing a DigitalOcean region (e.g. <code class="docutils literal notranslate"><span class="pre">nyc1</span></code>). If set, only volume snapshots available in the region will be returned.</p></li>
</ul>
</dd>
</dl>
</dd></dl>

<dl class="py function">
<dt id="pulumi_digitalocean.get_vpc">
<code class="sig-prename descclassname">pulumi_digitalocean.</code><code class="sig-name descname">get_vpc</code><span class="sig-paren">(</span><em class="sig-param"><span class="n">id</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">name</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">region</span><span class="o">=</span><span class="default_value">None</span></em>, <em class="sig-param"><span class="n">opts</span><span class="o">=</span><span class="default_value">None</span></em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_digitalocean.get_vpc" title="Permalink to this definition">¶</a></dt>
<dd><p>Use this data source to access information about an existing resource.</p>
<dl class="field-list simple">
<dt class="field-odd">Parameters</dt>
<dd class="field-odd"><ul class="simple">
<li><p><strong>id</strong> (<em>str</em>) – The unique identifier of an existing VPC.</p></li>
<li><p><strong>name</strong> (<em>str</em>) – The name of an existing VPC.</p></li>
<li><p><strong>region</strong> (<em>str</em>) – The DigitalOcean region slug for the VPC’s location.</p></li>
</ul>
</dd>
</dl>
</dd></dl>

</div>
