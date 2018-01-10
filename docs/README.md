# SVG Pocket Guide

> "Pocket Guide to Writing SVG" by Joni Trythall

## 目录

* [简介](#简介)
	* [前言](#前言)
		* [使用SVG](#使用SVG)
		* [矢量图形软件](#矢量图形软件)
		* [Web中的内联SVG](#Web中的内联SVG)
		* [SVG用户可访问性](#SVG用户可访问性)
		* [注意事项](#注意事项)
* [第1节： 文档组织](#第1节-文档组织)
	* [组织和语义](#组织和语义)
		* [svg元素](#svg元素)
		* [g元素](#g元素)
		* [use元素](#use元素)
		* [defs元素](#defs元素)
		* [symbol元素](#symbol元素)
	* [堆叠顺序](#堆叠顺序)
* [第2节：基本图形和路径](#第2节-基本图形和路径)
	* [基本图形](#基本图形)
		* [矩形](#矩形)
		* [圆形](#圆形)
		* [椭圆](#椭圆)
		* [直线](#直线)
		* [折线](#折线)
		* [多边形](#多边形)
	* [路径元素](#路径元素)
		* [path数据](#path数据)
			* [moveto](#moveto)
			* [closepath](#closepath)
			* [lineto](#lineto)
				* [L, l](#l-l)
				* [H, h](#h-h)
				* [V, v](#v-v)
			* [曲线命令](#曲线命令)
				* [Cubic Bézier](#cubic-bézier)
				* [Quadratic Bézier](#quadratic-bézier)
				* [Elliptical Arc](#elliptical-arc)
	* [矢量软件嵌入](#矢量软件嵌入)
* [第3节: 工作区域](#第3节-工作区域)
	* [viewport](#viewport)
	* [viewBox](#viewbox)
		* [preserveAspectRatio](#preserveaspectratio)
	* [坐标系统变换](#坐标系统变换)
		* [translate](#translate)
		* [rotate](#rotate)
		* [scale](#scale)
		* [skew](#skew)
* [第4节: 填充和描边](#第4节-填充和描边)
	 * [fill属性](#fill属性)
	 	* [fill-rule](#fill-rule)
	 	* [fill-opacity](#fill-opacity)
	 * [stroke属性](#stroke属性)
	 	* [stroke](#stroke)
	 	* [stroke-width](#stroke-width)
	 	* [stroke-linecap](#stroke-linecap)
	 	* [stroke-linejoin](#stroke-linejoin)
	 		* [stroke-miterlimit](#stroke-miterlimit)
	 	* [stroke-dasharray](#stroke-dasharray)
	 	* [stroke-dashoffset](#stroke-dashoffset)
	 	* [stroke-opacity](#stroke-opacity)
* [第5节: text元素](#第5节-text元素)
	* [基本属性](#基本属性)
		* [x, y, dx, dy](#x-y-dx-dy)
		* [rotate](#rotate)
		* [textLength和lengthAdjust](#textlength和lengthadjust)
	* [tspan元素](#tspan元素)
	* [间距属性](#间距属性)
		* [kerning和letter-spacing](#kerning和letter-spacing)
		* [word-spacing](#word-spacing)
	* [text-decoration](#text-decoration)
	* [沿着路径的文本](#沿着路径的文本)
		* [textPath元素](#textpath元素)
		* [xlink:href](#xlinkhref)
		* [startOffset](#startoffset)
* [第6节: 高级特性——渐变，图案，剪辑路径](#第6节-高级特性-渐变-纹理-剪辑路径)
	* [渐变](#渐变)
		* [线性渐变](#线性渐变)
			* [停止节点](#停止节点)
			* [x1, y1, x2, y2](#x1-y1-x2-y2)
			* [gradientUnits](#gradientunits)
			* [spreadMethod](#spreadmethod)
			* [gradientTransform](#gradienttransform)
			* [xlink:href](#xlinkhref-1)
		* [径向渐变](#径向渐变)
		* [cx, cy, r](#cx-cy-r)
		* [fx, fy](#fx-fy)
	* [图案](#纹理)
		* [基本属性](#基本属性)
			* [x, y, width, height](#x-y-width-height)
			* [patternUnits](#patternunits)
			* [patternContentUnits](#patterncontentunits)
		* [图案嵌套](#纹理嵌套)
	* [剪辑路径](#剪辑路径)
* [总结](#总结)