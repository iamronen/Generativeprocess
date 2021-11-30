/* Hide file names in transclusion */
div.markdown-embed-title {
	display: none;
}

/* Remove excessive borders in transclusion */
.markdown-preview-view .markdown-embed, .markdown-preview-view .file-embed {
	border-bottom: none; !important;
}

/* increase numbers in ordered list in transclusion */
::marker {
	font-size: var(--editor-font-size) !important;
}


/* Remove scroll bar from transclusions */
.markdown-preview-view .markdown-embed-content {
    max-height: unset;
}
.markdown-preview-view .markdown-embed-content > .markdown-preview-view {
    max-height: unset;
}