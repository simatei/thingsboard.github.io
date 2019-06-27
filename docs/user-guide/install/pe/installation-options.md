---
layout: docwithnav
assignees:
- ashvayka
title: ThingsBoard Professional Edition installation options
description: ThingsBoard Professional Edition installation instructions for various operation systems and cloud platforms
notitle: "true"
---

<div class="installation-options">
    <div class="install-options-header">
       <div class="install-options-hero">
          <div class="container">
            <div class="install-options-hero-content">
                <h1>ThingsBoard Professional Edition installation options</h1>
                <div class="install-options-description">
                    <p>
                        ThingsBoard Professional Edition is designed to run and utilize on majority of hardware, from local Raspberry PI to powerful servers in the cloud
                    </p>
                </div>
            </div>
            <div class="col-lg-12 deployment-container">
                <div class="deployment-selector">
                    <div class="deployment" data-toggle="#liveDemo">
                        <input type="radio" class="magic-radio" name="deployment-radio-selector" id="DeploymentLiveDemo" value="Deployment Live Demo Details">
                        <label for="DeploymentLiveDemo">
                            <div class="deployment-icon-div d-inline-block">
                                <img src="/images/install/live-demo.png" alt="live demo icon" class="live-demo-icon d-inline">
                            </div>
                            <h2 class="d-none d-md-inline-block">Live demo</h2>
                        </label>
                    </div>
                    <div class="deployment active" data-toggle="#onPremise">
                        <input type="radio" class="magic-radio" name="deployment-radio-selector" id="DeploymentOnPremise" value="Deployment On Premise Details" checked>
                        <label for="DeploymentOnPremise">
                            <div class="deployment-icon-div d-inline-block">
                                <img src="/images/install/on-premise.png" alt="on premise icon" class="on-premise-icon d-inline">
                            </div>
                            <h2 class="d-none d-md-inline-block">On premise</h2>
                        </label>
                    </div>
                    <div class="deployment" data-toggle="#cloud">
                        <input type="radio" class="magic-radio" name="deployment-radio-selector" id="DeploymentCloud" value="Deployment Cloud Details">
                        <label for="DeploymentCloud">
                            <div class="deployment-icon-div d-inline-block">
                                <img src="/images/install/cloud.png" alt="cloud icon" class="cloud-icon d-inline">
                            </div>
                            <h2 class="d-none d-md-inline-block">Cloud</h2>
                        </label>
                    </div>
                </div>
                <div class="deployment-div">
                    <div class="container">
                        <div class="deployment-section deployment-live-demo" id="liveDemo">
                            <div class="deployment-cards">
                                <div class="deployment-cards-container">
                                    <div class="deployment-card-block">
                                        <a href="https://demo.thingsboard.io/signup">
                                            <span>
                                                <div class="deployment-logo" style="height:134px">
                                                    <img width="" src="/images/install/live-demo/signup-ce.png" title="Live Demo" alt="Live Demo">
                                                 </div>
                                            </span>
                                        </a>
                                    </div>
                                </div>
                            </div>
                        </div>
                        <div class="deployment-section deployment-on-premise active" id="onPremise">
                           <div class="deployment-cards">
                                <div class="deployment-cards-container">
                                    <div class="deployment-card-block">
                                        <a href="/docs/user-guide/install/linux/">
                                            <span>
                                                <div class="deployment-logo" style="height:134px">
                                                    <img width="" src="/images/install/platform/ubuntu.png" title="Ubuntu" alt="Ubuntu">
                                                 </div>
                                            </span>
                                        </a>
                                    </div>
                                    <div class="deployment-card-block">
                                        <a href="/docs/user-guide/install/linux/">
                                            <span>
                                                <div class="deployment-logo" style="height:134px">
                                                    <img width="" src="/images/install/platform/centos-redhat.png" title="CentOS/RHEL" alt="CentOS/RHEL">
                                                 </div>
                                            </span>
                                        </a>
                                    </div>
                                    <div class="deployment-card-block">
                                        <a href="/docs/user-guide/install/windows/">
                                            <span>
                                                <div class="deployment-logo" style="height:134px">
                                                    <img width="" src="/images/install/platform/windows.png" title="Windows" alt="Windows">
                                                 </div>
                                            </span>
                                        </a>
                                    </div>
                                    <div class="deployment-card-block">
                                        <a href="/docs/user-guide/install/rpi/">
                                            <span>
                                                <div class="deployment-logo" style="height:134px">
                                                    <img width="" src="/images/install/platform/rpi3.jpg" title="Raspberry Pi 3" alt="Raspberry Pi 3">
                                                 </div>
                                            </span>
                                        </a>
                                    </div>
                                    <div class="deployment-card-block">
                                        <a href="/docs/user-guide/install/docker-windows/">
                                            <span>
                                                <div class="deployment-logo" style="height:134px">
                                                    <img width="" src="/images/install/platform/docker-windows.png" title="Docker (Windows)" alt="Docker (Windows)">
                                                 </div>
                                            </span>
                                        </a>
                                    </div>
                                    <div class="deployment-card-block">
                                        <a href="/docs/user-guide/install/docker/">
                                            <span>
                                                <div class="deployment-logo" style="height:134px">
                                                    <img width="" src="/images/install/platform/docker-linux-macos.png" title="Docker (Linux or Mac OS)" alt="Docker (Linux or Mac OS)">
                                                 </div>
                                            </span>
                                        </a>
                                    </div>
                                    <div class="deployment-card-block">
                                        <a href="/docs/user-guide/install/cluster-setup/">
                                            <span>
                                                <div class="deployment-logo" style="height:134px">
                                                    <img width="" src="/images/install/platform/cluster.png" title="Cluster setup" alt="Cluster setup">
                                                 </div>
                                            </span>
                                        </a>
                                    </div>
                               </div>                    
                            </div>                        
                        </div>
                        <div class="deployment-section deployment-cloud" id="cloud">
                            <div class="deployment-cards">
                                <div class="deployment-cards-container">
                                    <div class="deployment-card-block">
                                        <a href="/docs/user-guide/install/aws/">
                                            <span>
                                                <div class="deployment-logo" style="height:134px">
                                                    <img width="" src="/images/install/cloud/aws.png" title="AWS" alt="AWS">
                                                 </div>
                                            </span>
                                        </a>
                                    </div>
                                    <div class="deployment-card-block">
                                        <a href="/docs/user-guide/install/aws/">
                                            <span>
                                                <div class="deployment-logo" style="height:134px">
                                                    <img width="" src="/images/install/cloud/gcp.png" title="Google Cloud Platform" alt="Google Cloud Platform">
                                                 </div>
                                            </span>
                                        </a>
                                    </div>
                                    <div class="deployment-card-block">
                                        <a href="/docs/user-guide/install/aws/">
                                            <span>
                                                <div class="deployment-logo" style="height:134px">
                                                    <img width="" src="/images/install/cloud/azure.png" title="Microsoft Azure" alt="Microsoft Azure">
                                                 </div>
                                            </span>
                                        </a>
                                    </div>
                                    <div class="deployment-card-block">
                                        <a href="/docs/user-guide/install/aws/">
                                            <span>
                                                <div class="deployment-logo" style="height:134px">
                                                    <img width="" src="/images/install/cloud/digitalocean.png" title="Digital Ocean" alt="Digital Ocean">
                                                 </div>
                                            </span>
                                        </a>
                                    </div>
                                    <div class="deployment-card-block">
                                        <a href="/docs/user-guide/install/aws/">
                                            <span>
                                                <div class="deployment-logo" style="height:134px">
                                                    <img width="" src="/images/install/cloud/ibm-cloud.png" title="IBM Cloud" alt="IBM Cloud">
                                                 </div>
                                            </span>
                                        </a>
                                    </div>
                                    <div class="deployment-card-block">
                                        <a href="/docs/user-guide/install/aws/">
                                            <span>
                                                <div class="deployment-logo" style="height:134px">
                                                    <img width="" src="/images/install/cloud/alibaba-cloud.jpg" title="Alibaba Cloud" alt="Alibaba Cloud">
                                                 </div>
                                            </span>
                                        </a>
                                    </div>
                               </div>                    
                            </div>                                                      
                        </div>
                    </div>
                </div>    
            </div>            
          </div>
       </div>
    </div>
</div>

<script type="text/javascript">

    inViewportDefer(function() {
        $(".deployment-cards .deployment-cards-container .deployment-card-block").inViewport(function(px){
            if(px >= 10) {
                $(this).addClass("animated zoomIn");
                return true;
            }
        });
    });

    jqueryDefer(function () {
        $('.deployment-selector .deployment').click(function(event) {
            event.preventDefault();
            var id = $(this).attr("data-toggle");
            $(this).find(".magic-radio").prop("checked", true);
            $('.deployment-selector .deployment').removeClass("active");
            $(this).addClass("active");
            $('.deployment-div .deployment-section').removeClass("active");
            $('.deployment-div .deployment-section'+id).addClass("active");
            
            $('.deployment-div .deployment-section' + id + ' .deployment-card-block').addClass("animated zoomIn");
            
        });

    });

</script>