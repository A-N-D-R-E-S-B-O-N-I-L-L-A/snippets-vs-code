### Snippets for my visual studio code

```
{
	// Place your snippets for javascript here. Each snippet is defined under a snippet name and has a prefix, body and 
	// description. The prefix is what is used to trigger the snippet and the body will be expanded and inserted. Possible variables are:
	// $1, $2 for tab stops, $0 for the final cursor position, and ${1:label}, ${2:another} for placeholders. Placeholders with the 
	// same ids are connected.
	// Example:
	// "Print to console": {
	// 	"prefix": "log",
	// 	"body": [
	// 		"console.log('$1');",
	// 		"$2"
	// 	],
	// 	"description": "Log output to console"
	// }
	"React Native Styles": {
		"prefix": "stles",
		"body": [
			"const styles = StyleSheet.create({",
			"    $1",
			"});"
		]
	},
	"React Native Component": {
		"prefix": "rnafc",
		"body": [
			"import React from 'react'",
			"import { StyleSheet, Text, View } from 'react-native'",
			"",
			"export const $1 = () => {",
			"  return (",
			"    <View>",
			"        <Text>$1 is working</Text>",
			"    </View>",
			"  )",
			"}",
			"",
			"const styles = StyleSheet.create({",
			"",
			"});"
		]
	},
	"Interface React Native Props": {
		"prefix": "rnprops",
		"body": [
			"interface Props extends StackScreenProps<RootStackParams, ''>{};",
		]
	},
	"Next Document Component": {
		"prefix": "nextdoc",
		"body": [
			"import { Html, Head, Main, NextScript } from 'next/document'",
			"export default function Document() {",
			" return (",
			"   <Html>",
			"      <Head />",
			"      <body>",
			"          <Main />",
			"          <NextScript />",
			"      </body>",
			"   </Html>",
			" )",
			"}"
		]
	},
	"Get Server Side Props": {
		"prefix": "getserverside",
		"body": [
			"export const getServerSideProps = async(ctx) => {",
			"  return {",
			"    props: {},",
			"  }",
			"}"
		]
	},
	"Get Static Paths": {
		"prefix": "getstaticpaths",
		"body": [
			"export const getStaticPaths = async(ctx) => {",
			"  return {",
			"    paths: [],",
			"    fallback: 'blocking'",
			"  }",
			"}"
		]
	},
	"Get Static Props": {
		"prefix": "getstaticprops",
		"body": [
			"export const getStaticProps = async({ params }) => {",
			"  return {",
			"    props: {},",
			"    revalidate: 60 * 60 * 24",
			"  }",
			"}"
		]
	},
	"Create Next Route": {
		"prefix": "nextroute",
		"body": [
			"export default async function handler(req, res) {",
			"",
			"  res.status(200).json({",
			"    message: 'Hello world'",
			"  })",
			"",
			"}"
		]
	},
	"Create JavaScript Function": {
		"prefix": "jsfunction",
		"body": [
			"const $1 = () => {",
			"",
			"}"
		]
	}
}
```
