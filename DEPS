# This file is used to manage Vulkan dependencies for several repos. It is
# used by gclient to determine what version of each dependency to check out, and
# where.

# Avoids the need for a custom root variable.
use_relative_paths = True
git_dependencies = 'SYNC'

vars = {
  'chromium_git': 'https://chromium.googlesource.com',

  # Current revision of glslang, the Khronos SPIRV compiler.
  'glslang_revision': 'a8d28bd082bff18ffbe80996e922b012f915cf07',

  # Current revision of Lunarg VulkanTools
  'lunarg_vulkantools_revision': 'fa705f5c11aacd29abc9733591e9697e015a145b',

  # Current revision of spirv-cross, the Khronos SPIRV cross compiler.
  'spirv_cross_revision': 'b8fcf307f1f347089e3c46eb4451d27f32ebc8d3',

  # Current revision fo the SPIRV-Headers Vulkan support library.
  'spirv_headers_revision': '4015a331f5ffd6fc5c6fa7b03e08fb4a692491d7',

  # Current revision of SPIRV-Tools for Vulkan.
  'spirv_tools_revision': 'd993bcfafa3c6dd9c0ba0560ae1456a62fd78e07',

  # Current revision of Khronos Vulkan-Headers.
  'vulkan_headers_revision': '11d6898377797e07dbd543aaaa367e4465074597',

  # Current revision of Khronos Vulkan-Loader.
  'vulkan_loader_revision': '06830240f7a70599053f47b5f10af543e8c3daf6',

  # Current revision of Khronos Vulkan-Tools.
  'vulkan_tools_revision': 'a354dc33efa5f0f30fae6db9c198116b6bda584f',

  # Current revision of Khronos Vulkan-Utility-Libraries.
  'vulkan_utility_libraries_revision': 'ca91449653e1a29b4b3c1876d7f6e1dcda08cfdd',

  # Current revision of Khronos Vulkan-ValidationLayers.
  'vulkan_validation_revision': '79576d4b3ba94bbd4a4c842486ec88779ea58514',
}

deps = {
  'glslang/src': {
    'url': '{chromium_git}/external/github.com/KhronosGroup/glslang@{glslang_revision}',
  },

  'lunarg-vulkantools/src': {
    'url': '{chromium_git}/external/github.com/LunarG/VulkanTools@{lunarg_vulkantools_revision}',
  },

  'spirv-cross/src': {
    'url': '{chromium_git}/external/github.com/KhronosGroup/SPIRV-Cross@{spirv_cross_revision}',
  },

  'spirv-headers/src': {
    'url': '{chromium_git}/external/github.com/KhronosGroup/SPIRV-Headers@{spirv_headers_revision}',
  },

  'spirv-tools/src': {
    'url': '{chromium_git}/external/github.com/KhronosGroup/SPIRV-Tools@{spirv_tools_revision}',
  },

  'vulkan-headers/src': {
    'url': '{chromium_git}/external/github.com/KhronosGroup/Vulkan-Headers@{vulkan_headers_revision}',
  },

  'vulkan-loader/src': {
    'url': '{chromium_git}/external/github.com/KhronosGroup/Vulkan-Loader@{vulkan_loader_revision}',
  },

  'vulkan-tools/src': {
    'url': '{chromium_git}/external/github.com/KhronosGroup/Vulkan-Tools@{vulkan_tools_revision}',
  },

  'vulkan-utility-libraries/src': {
    'url': '{chromium_git}/external/github.com/KhronosGroup/Vulkan-Utility-Libraries@{vulkan_utility_libraries_revision}',
  },

  'vulkan-validation-layers/src': {
    'url': '{chromium_git}/external/github.com/KhronosGroup/Vulkan-ValidationLayers@{vulkan_validation_revision}',
  },
}
