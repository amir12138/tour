<template>
    <section class="">
                <div class="figures">
                    <div></div>
                    <div>
                        <ul>
                            <li>丢掉手机丢手表</li>
                            <li>丢掉工作再丢辛苦</li>
                            <li>丢掉电视丢电脑</li>
                            <li>丢掉大脑再丢烦恼</li>
                            <li>…………</li>
                            <li>放下一切</li>
                            <li>留出一点点空白，挤出一丢丢时间</li>
                            <li>背上背包，带上money</li>
                            <li>来一场说走就走的旅行</li>
                        </ul>
                    </div>
                </div>
                <div class="text-block">
                    <ul class="block">
                        <li>
                            <ul>
                                <li class="text-one line-one"><p>旅行<br>对生命的一次自我流放</p></li>
                                <li class="one"><img :src="images[0]"></li>
                                <li class="text-two line-one row"><p>&nbsp;&nbsp;一个背包，几本书，所有喜欢的歌，一张单程车票，一颗潇洒的心。一个人的旅行，在路上遇见最真实的自己。</p></li>
                                <li class="text-one line-one"><p>旅行<br>对生命的一次自我流放</p></li>
                                <li class="image-two"><img :src="images[1]"></li>
                                <li class="text-two line-one"><p>&nbsp;&nbsp;我想去旅行，一个人背包，一个人旅行，一个人目睹沿途的风景，拿着相机，拍下沿途上的风景，记录沿途的情绪。</p></li>
                            </ul>
                        </li>
                        <li>
                            <ul>
                                <li class="text-one line-two"><p>旅行<br>对生命的一次自我流放</p></li>
                                <li class="two"><img :src="images[2]"></li>
                                <li class="text-two line-two row"><p>&nbsp;&nbsp;带上心灵去旅行，以平和的心态看待一切，文画音，看似耳目所为，其实是内心世界的感受。</p></li>
                                <li class="text-one line-two"><p>旅行<br>对生命的一次自我流放</p></li>
                                <li class="image-two"><img :src="images[3]"></li>
                                <li class="text-two line-two"><p>&nbsp;&nbsp;旅游，尝试着走出去，你才会发现，世界远不是你在出生的城市一呆几十年所看的那样，你会结识不一样的人听到各种曲折的故事交到一辈子的朋友。</p></li>
                            </ul>
                        </li>
                        <li>
                            <ul>
                                <li class="text-one line-three"><p>旅行<br>对生命的一次自我流放</p></li>
                                <li class="three"><img :src="images[4]"></li>
                                <li class="text-two line-three row"><p>&nbsp;&nbsp;人生至少要有两次冲动，一次奋不顾身的爱情，一次说走就走的旅行。</p></li>
                                <li class="text-one line-three"><p>旅行<br>对生命的一次自我流放</p></li>
                                <li class="image-two"><img :src="images[5]"></li>
                                <li class="text-two line-three"><p>&nbsp;&nbsp;背着背包的路上，看过许多人，听过许多故事，见过旅行风景，就这样，慢慢学会了长大。流转的时光，都成为命途中美丽的点缀，看天，看雪，安安静静，不言不语都是好风景。</p></li>
                            </ul>
                        </li>
                        <li>
                            <ul>
                                <li class="text-one line-four"><p>旅行<br>对生命的一次自我流放</p></li>
                                <li class="four"><img :src="images[6]"></li>
                                <li class="text-two line-four row"><p>&nbsp;&nbsp;赶快上路吧，不要有一天我们在对方的葬礼上说，要是当时去了就好了——《城市画报》</p></li>
                                <li class="text-one line-four"><p>旅行<br>对生命的一次自我流放</p></li>
                                <li class="image-two"><img :src="images[7]"></li>
                                <li class="text-two line-four"><p>&nbsp;&nbsp;对未知的恐惧，对舒适的留恋将阻止我们成为一个旅行者走上的冒险旅程。但是，当你作出这样的选取，你就永远不会后悔。——《我们为什么要旅行》</p></li>
                            </ul>
                        </li>
                        <li>
                            <ul>
                                <li class="text-one line-five"><p>旅行<br>对生命的一次自我流放</p></li>
                                <li class="five"><img :src="images[8]"></li>
                                <li class="text-two line-five"><p>&nbsp;&nbsp;每个人在他的人生发轫之初，总有一段时光，没有什么可留恋，只有抑制不住的梦想，没有什么可凭仗，只有他的好身体，没有地方可去，只想到处流浪。</p></li>
                            </ul>
                        </li>
                    </ul>
                </div>
        <footer>
            <div class="connections">
                <ul>
                    <li><img :src="images[9]"></li>
                    <li><a href="">关于我们</a></li>
                    <li>丨</li>
                    <li><a href="">意见反馈及投诉</a></li>
                    <li>丨</li>
                    <li><a href="">用户协议</a></li>
                    <li>丨</li>
                    <li><a href="">隐私政策</a></li>
                    <li>丨</li>
                    <li><a href="">免责声明</a></li>
                    <li>丨</li>
                    <li><a href="">网站大全</a></li>
                    <li>Copyright&copy;2017 LiuDianBai.com. All Rights Reserved</li>
                    <li>京ICP证050897号</li>
                </ul>
            </div>
        </footer>
    </section>
</template>

<script>
    let image1 = require("../../images/block01.png");
    let image2 = require("../../images/block02.png");
    let image3 = require("../../images/block03.png");
    let image4 = require("../../images/block04.png");
    let image5 = require("../../images/block05.png");
    let image6 = require("../../images/block06.png");
    let image7 = require("../../images/block07.png");
    let image8 = require("../../images/block08.png");
    let image9 = require("../../images/block09.png");
    let image10 = require("../../images/footer.png");

    let images=[image1,image2,image3,image4,image5,image6,image7,image8,image9,image10];

    export default {
        data:() => ({
        images
        }),
        name: "homepage"
    }
</script>
<style>
  /* @import '../../stylesheets/homepage.css'; */
	div.figures{
		clear: both;
		width: 1899px;
		height: 480px;
		background-image: url(../../images/header.jpg);
		background-size: 100% 100%;
		display: inline-block;
		position: relative;
	}
	div.figures>div:first-child{
		background: rgba(0,0,0,0.3);
	}
	div.figures>div{
		width: 1899px;
		height: 480px;
		position: absolute;
		top: 0px;
	}
	div.figures>div>ul{
		display: block;
		margin: 0 auto;
		width: 784px;
		text-align: center;
		margin-top: 60px;
	}
	div.figures li{
		display: block;
		font-size: 20px;
		color: white;
		margin-top: 20px;
	}
	div.text-block{
		width: 1899px;
		height: 1520px;
		display: inline-block;
		background-color: #e8f7fe;
	}
	ul.block{
		width: 1764px;
		height: 1350px;
		margin: 0 auto;
		margin-top: 50px;
		display: flex;
		justify-content: space-between;
		font-family: "黑体";
		color: white;
	}
	ul.block>li{
		float: left;
		width: 335px;
		height: 1350px;
	}
	ul.block>li>ul>li{
		width: 335px;
		vertical-align: bottom;
	}
	ul.block img{
		width: 100%;
		height: 100%;
	}
	li.text-one{
		height: 100px;
		margin-top: 10px;
		font-size: 22px;
	}
	li.text-one>p{
		padding: 18px;
		text-align: center;
	}
	li.image-two{
		height: 600px;
	}
	li.text-two{
		height: 130px;
	}
	li.text-two>p{
		padding: 18px;
	}
	li.row{
		height: 100px;
	}
	li.one{
		height: 240px;
	}
	li.two{
		height: 270px;
	}
	li.three{
		height: 300px;
	}
	li.four{
		height: 330px;
	}
	li.five{
		height: 1170px;
	}
	li.line-one{
		background: #00cacc;
	}
	li.line-two{
		background: #6dbb48;
	}
	li.line-three{
		background: #9cdaf5;
	}
	li.line-four{
		background: #846edb;
	}
	li.line-five{
		background: #3461ee;
	}
	footer{
		width: 100%;
		background: #333;
		border-top: 1px solid #aaa;
	}
	.connections{
		margin-top: 20px;
		height: 40px;
	}
	.connections ul{
		display: flex;
		width: 920px;
		font-size: 13px;
		margin: 0 auto;
		color: #fff;
	}
	.connections li:nth-child(13){
		margin-left: 15px;
		color: #aaa;
	}
	.connections img{
		display: inline-block;
		width: 20px;
		height: 20px;
	}
	.connections a{
		color: #fff;
	}
	.connections a:hover{
		text-decoration: underline;
	}
</style>